# Getting started

[Български](bg/getting-started.md) · [Docs index](README.md)

TEKSO starts in English. To change the language, see [Language and themes](#language-and-themes).

## The start screen

When TEKSO opens you see **Welcome**. From here you can:

- Click **New text document**, **Open spreadsheet…**, **Open presentation…** or **Open PDF…**.
- Drag a file onto the window. TEKSO recognises the type by itself.
- Pick a file under **Recent**, or try one of the **Sample documents**.

To come back to this screen later, use **File → Home screen**.

## Open and create

| You want | Do this |
|---|---|
| Text | **New text document**, or open a `.docx` |
| Spreadsheet | **Open spreadsheet…** and choose an `.xlsx` |
| Slides | **Open presentation…** and choose a `.pptx` |
| PDF | **Open PDF…** |
| A file TEKSO cannot recognise | **File → Open as…** and pick a mode |

OpenDocument files (`.odt`, `.ods`, `.odp`) can be read. Each document opens in its own tab.

## Save

Press **Save** (**File → Save**, ⌘S on macOS, Ctrl+S on Windows). Text is saved as `.docx`, spreadsheets as `.xlsx` and presentations as `.pptx`. Text can also be exported with **Export as PDF**.

- **Version history:** the **Versions…** command saves named versions of a text document. They are stored in a file called `<document>.tekso-versions` next to the document. If you move the document, move that file too.
- **Recovery:** every 8 seconds TEKSO keeps a safety copy of changed documents. After an interruption, the start screen offers **Review and restore**. Your original files are not touched.

## PDF

Open a PDF to view it, edit it and fill in forms. The PDF tabs include **Form and signature** and **Check**.

- **Accessibility:** **Accessibility: figures without alt text** lists pictures that have no description. You write the alt text yourself. TEKSO does not invent it.
- **PDF/A:** **Check PDF/A** tests a file. **Save a copy as PDF/A…** creates an archive copy and tells you if anything is left to fix. **Check PDF/UA (accessibility)** tests accessibility. These are checks, not a legal guarantee.
- **Forms:** fill in the fields directly. If the document is already signed, TEKSO warns you that filling it will show the signature as modified.

## Sign with a qualified electronic signature (QES/КЕП)

You need a smart card, a card reader and the software of the card's maker installed.

1. Open the PDF and go to **Form and signature**.
2. Click **Sign with QES…**.
3. Choose the card. If TEKSO does not find your card, open **Settings… → Signature** and enter the path to the card module (**Card module (PKCS#11)**). It is a `.dylib` on macOS and a `.dll` on Windows. Then search for cards again.
4. Pick the certificate marked **for signing**.
5. Enter the PIN. If the card has few attempts left, TEKSO warns you first. Switch your keyboard to English before typing the PIN.
6. Click **Sign**, then **Save**.

Use **Verify signatures** to see what was and what was not checked. The PIN is never saved. Whether a signature is legally "qualified" depends on your certificate provider, your card and the validity of your certificate. TEKSO is a tool, not legal advice.

## Language and themes

Open **Settings…** (⌘, on macOS).

- **Interface language:** choose English or Bulgarian. The change applies the next time you start the app.
- **Theme:** light, dark, or follow the system. The button in the top bar also cycles through these.
- **Color theme:** **Pure Ink** (default), **System (Clear)**, **Saffron**, **Emerald & Brass**, **Midnight Coral**.

## Help from AI

See [AI and MCP](ai-and-mcp.md). It is off until you turn it on.
