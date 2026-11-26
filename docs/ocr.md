# OCR accuracy and limits

[Български](bg/ocr.md) · [Docs index](README.md)

TEKSO reads scanned pages on your computer with bundled models. Nothing is uploaded. Bulgarian, English and other Cyrillic and Latin text are read together.

These numbers come from our own test, so read them as a guide, not a promise:

- **Synthetic pages, not real scans.** We rendered 8 pages from known text (Bulgarian prose in Arial, Times New Roman, Verdana, Georgia and Tahoma at 7 to 12 pt, a table with ruled cells, English text, two columns, text mixed with numbers and Latin words) and degraded each one 8 ways, which gives 64 images, 54,080 characters and 8,544 words.
- **Not measured:** photos of paper, folds and stains, stamps over text, handwriting, rotated or mirrored pages, languages other than Bulgarian and English, and real office scans from a scanner or phone. Accuracy there can be clearly worse.
- Error rates are against the known text: **CER** is the share of wrong characters, **WER** the share of wrong words (a word with one wrong letter counts as wrong). Lower is better. Measured on a Mac with an M4 chip.

## Result (beta, default settings)

Across all 64 images: **0.53 % of characters and 2.6 % of words wrong** (about 1 wrong word in 38).

| Image quality | Characters wrong | Words wrong |
|---|---|---|
| Clean, 300 dpi | 0.38 % | 1.7 % |
| Clean, 200 dpi | 0.41 % | 2.3 % |
| Clean, 150 dpi | 0.46 % | 2.3 % |
| Slightly blurred, 300 dpi | 0.55 % | 2.2 % |
| Rotated by 1 degree, 200 dpi | 0.41 % | 2.2 % |
| Rotated by 2 degrees, 200 dpi | 0.47 % | 2.4 % |
| Faded (grey text on grey paper), 200 dpi | 0.67 % | 3.7 % |
| 150 dpi, blurred, noisy, rotated 1.5 degrees, JPEG | 0.86 % | 4.5 % |

By page type (all 8 qualities together):

| Page | Characters wrong | Words wrong |
|---|---|---|
| Bulgarian prose, 11 pt and 12 pt | 0.0 % and 0.1 % | 0.0 % and 0.9 % |
| English, 11 pt | 0.0 % | 0.0 % |
| Table with ruled cells, 10 pt | 0.9 % | 3.4 % |
| Bulgarian serif, 9 pt | 0.4 % | 2.8 % |
| Small print, 7 pt | 0.3 % | 1.9 % |
| Two columns, 9.5 pt | 1.2 % | 7.0 % |
| Text with numbers, codes and Latin words, 10 pt | 1.6 % | 5.0 % |

Speed on the same Mac: a median of about 0.65 second per A4 page (the 150 to 300 dpi images above, automatic number of threads). Other computers, scans with more text and the first page after start can take longer.

## Where it is weak

- **Small print on poor scans.** Before this change the detector looked at pages at a smaller size, and 7 pt text that was blurred, faded or scanned at 150 dpi lost whole lines (12 to 33 % of characters wrong). It now looks at a larger size and the same pages are at 0.2 to 0.9 %. The cost is a few percent more time. This was tuned on our synthetic set only.
- **Letters that look alike.** The Bulgarian hard sign and the soft sign are confused in small print ("първа" read as "пьрва"). In text with numbers and Latin words, `0` and `O`, `6` and `б`, and Cyrillic and Latin capitals are mixed up ("ISO" as "IS0", "ДДС" as "DDC"). TEKSO fixes some look-alike letters inside Cyrillic words, not all. Always check numbers, codes and names.
- **Columns.** Two columns are read one after the other, but a column break in the middle of a sentence can still go wrong, and the word error rate is the highest here (7 %).
- **Tables.** A table with ruled cells was read cell by cell in our test (0.9 % of characters wrong). A table without ruling, merged cells and tables in photos were not measured. When exported to Word or OpenDocument, table cells come out as lines of text, not as a table.
- **Slanted pages.** TEKSO straightens up to about 5 degrees. Our test only went to 2 degrees.
- **Editable mode on slanted scans.** In "Editable text" mode a page that is slightly tilted (1.5 and 2 degrees in our test) can read back with broken line order when its text is extracted from the saved PDF (up to 24 % of characters wrong in that reading). We have not looked at how such a page looks on screen. For tilted scans use the invisible text layer (the default) until this is checked.

## Checked from start to finish

We also ran 14 of the images through the AI connector (`pdf_ocr`) to a searchable PDF, an editable PDF, a Word file and an OpenDocument file. The Word and OpenDocument files held the same text as the invisible layer in every case (identical error rates). The editable PDF gave the same text on 10 of the 14 images and was worse on the 4 tilted ones (rotated 1.5 or 2 degrees), slightly on two of them and badly on two (see above). These files were read back as text; they were not opened in Word, LibreOffice or Acrobat.

## How to get better results

- Scan at 200 to 300 dpi, straight, with good contrast. 150 dpi works for normal print, but small print benefits from more.
- Keep the page flat and the text dark on light paper.
- Open the low-confidence words the app marks and check numbers, dates, IBANs and names by eye. Recognition can be wrong.
