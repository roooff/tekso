# Privacy

[Български](bg/privacy.md) · [Docs index](README.md)

## What leaves your computer

Nothing, with two exceptions.

1. **What you give to an AI.** If you connect an AI assistant, the documents you let it read go to that provider and are handled under its terms. See [AI and MCP](ai-and-mcp.md).
2. **GitHub download logs.** When you download TEKSO from this page, GitHub sees your request (for example your IP address) and counts downloads, under GitHub's terms.

TEKSO has no account, no cloud, no telemetry and no automatic update checks.

## Where your data lives

- **Your documents:** where you save them.
- **Version history:** files named `<document>.tekso-versions` next to your documents.
- **Recovery copies and TEKSO data:** the folder `~/.tekso` on macOS, and `%APPDATA%\TEKSO` on Windows.
- **Settings:** stored on your computer by the app (such as theme and language).

## Delete your data

1. Quit TEKSO.
2. Delete the data folder: `~/.tekso` (macOS) or `%APPDATA%\TEKSO` (Windows).
3. Delete `*.tekso-versions` files next to documents if you no longer want the history.
4. Uninstall the app: see [Install](install.md#uninstall).

The system also keeps a few small app folders with interface settings (theme, language, window size). Delete them too for a complete removal:

- **macOS:** `~/Library/WebKit/app.tekso`, `~/Library/Caches/app.tekso` and `~/Library/Preferences/app.tekso.plist`.
- **Windows:** `%LOCALAPPDATA%\app.tekso`.

Your documents are never deleted by uninstalling.

Questions: hello@tekso.app
