# FAQ

[Български](bg/faq.md) · [Docs index](README.md)

**Why is the installer unsigned?**
Code signing certificates cost money and the beta is free. Signing will come with the paid version. Until then your system asks once on first launch. See [Install](install.md#4-first-launch-of-an-unsigned-app) and verify the SHA-256 of your download.

**Does TEKSO update itself?**
It checks GitHub for a newer version at start, downloads it and installs it only when you click. You can turn the check off. See [Install](install.md#update).

**How much will it cost?**
Free during the beta, which has no end date. Later about 5 to 7 EUR per year. The price is not final. It will be announced at least 30 days before it starts, nothing is charged without your consent, and an installed beta does not become paid retroactively. See [EULA](../EULA.md), section 3.

**Does it work with Microsoft Office files?**
It opens and saves `.docx`, `.xlsx` and `.pptx`. It also opens `.odt` (saved back as `.odt`), `.ods`, `.odp`, `.doc`, `.rtf`, `.md`, `.txt`, `.html`, `.xls`, `.xlsb`, `.csv` and `.tsv`; those other formats are imported and saved as `.docx`, `.xlsx` or `.pptx`. It cannot open `.epub`. Compatibility is best effort. Complex documents may look different in other programs. Keep backups of important files.

**Is my QES signature legally valid?**
It depends on your certificate provider, your card and the validity of your certificate. TEKSO is a tool, not legal advice.

**Is my data sent anywhere?**
Your documents are not. The app asks GitHub whether there is a newer version, which you can turn off. See [Privacy](privacy.md).

**Known limits of the beta**
- No real-time collaboration. This is by design: TEKSO is local.
- No macros. They are kept in files but not run.
- No live multi-monitor presenting.
- No screen-reader support yet.
- Arabic text in PDF/A is limited.
- OCR was measured on synthetic pages only, not on real scans. See [OCR accuracy and limits](ocr.md).
- macOS: Apple Silicon only for now.

**I found a bug.**
Open an issue in the **Issues** tab. Do not post personal or confidential documents. For security problems write to security@tekso.app instead.
