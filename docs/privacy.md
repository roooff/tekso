# Privacy

[Български](bg/privacy.md) · [Docs index](README.md)

## What leaves your computer

Your documents do not leave it. There are three cases in which something goes over the network.

1. **What you give to an AI.** If you connect an AI assistant, the documents you let it read go to that provider and are handled under its terms. See [AI and MCP](ai-and-mcp.md).
2. **GitHub download logs.** When you download TEKSO from this page, GitHub sees your request (for example your IP address) and counts downloads, under GitHub's terms.
3. **Check for new versions.** At start the app asks GitHub for a small file with the latest version number (`https://github.com/roooff/tekso/releases/download/updates/latest.json`) and, if there is a newer version, downloads it from the same releases. No documents, file names, settings, account or identifier are sent, and the address carries no information about you. As with any web request, GitHub (and the file server it redirects to) sees your IP address, the time and the name and version of the update component, under GitHub's terms. GitHub counts these downloads.

**Turning the check off:** untick **Check for new versions automatically** on the **Getting started** card, or switch it off in **Settings → General**. On the very first start no check is made, so you can turn it off first. When off, TEKSO checks only if you choose **Check for updates** in the menu. Without a network the check fails silently.

TEKSO has no account, no cloud and no telemetry.

## Where your data lives

- **Your documents:** where you save them.
- **Version history:** files named `<document>.tekso-versions` next to your documents.
- **Recovery copies and TEKSO data:** the folder `~/.tekso` on macOS, and `%APPDATA%\TEKSO` on Windows.
- **Settings:** stored on your computer by the app (such as theme and language).
- **Template drafts:** in versions with form templates, what you type into a template is kept as a draft in the app folders listed below. It may contain personal data. A draft is removed when you create the document from it.

TEKSO does not encrypt recovery copies, version history or drafts.

## Delete your data

1. Quit TEKSO.
2. Delete the data folder: `~/.tekso` (macOS) or `%APPDATA%\TEKSO` (Windows).
3. Delete `*.tekso-versions` files next to documents if you no longer want the history.
4. Uninstall the app: see [Install](install.md#uninstall).

The system also keeps a few app folders with interface settings (theme, language, window size) and any template drafts. Delete them too for a complete removal:

- **macOS:** `~/Library/WebKit/app.tekso`, `~/Library/Caches/app.tekso` and `~/Library/Preferences/app.tekso.plist`.
- **Windows:** `%LOCALAPPDATA%\app.tekso`.

Your documents are never deleted by uninstalling.

Questions: hello@tekso.app
