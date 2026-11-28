# AI and MCP

[Български](bg/ai-and-mcp.md) · [Docs index](README.md)

MCP (Model Context Protocol) is an open standard that lets an AI assistant such as Claude work with tools on your computer. With TEKSO it means the assistant can read and edit your documents. The AI part is **off by default**. TEKSO works fully without it.

## Turn it on in TEKSO

1. Open the Claude panel: click **Claude: off** in the status bar, or use **Settings… → Claude (MCP)** and **Open Claude panel**.
2. Turn on **Allow Claude access**.

The status bar then shows **Claude: on**. While it is off, every request from an AI is refused.

## Connect Claude Desktop

There are two ways. Choose one.

**A. The `.mcpb` package (files in a folder).** Download `tekso-macos.mcpb` (Mac) or `tekso-win32.mcpb` (Windows) from **Releases** and open it in Claude Desktop. The installer asks for three things:

- **Documents folder:** the assistant can only reach files inside this folder.
- **Read-only:** on by default. While it is on, the assistant cannot save or change files on disk.

- **Work in the open TEKSO window:** off by default. See B below.
- **Compact tools:** off by default. When on, Claude sees 47 core tools for text, sheets, presentations, PDF and forms. Charts, tracked changes, OCR, redaction, pictures, styles and mail merge need it off. It saves context; it is not a security restriction.

Turn read-only off only if you want the assistant to save changes to files in that folder.

**B. The documents open in TEKSO.** Install the same `.mcpb` package and turn on **Work in the open TEKSO window** in its settings in Claude Desktop. Then, in TEKSO, turn on **Allow Claude access** as above (and add folders in **Settings > Claude** if Claude should open files itself). You and the assistant then work on the same open document, with one shared Undo. Its changes are applied directly and it can save them; the package's Read only setting does not apply here, so turn on **Claude read-only (cannot write files)** in the Claude panel if it must not save. TEKSO must be open while you work this way.

## What the assistant can change

When it is allowed to write, the assistant changes documents directly; changes are not guaranteed to be shown as proposals first. Always check what it changed: AI can be wrong. Keep a copy of important files.

In the Claude panel you can:

- see who is connected and a **Log of calls on this document**;
- turn on **Claude read-only (cannot write files)**;
- click **Stop Claude** to turn access off at once;
- click **Undo everything from Claude** or **Revert everything** to go back. These change the open document; a file already saved stays as saved until you save again.

In text documents you can ask the assistant to make its edits as tracked changes. Then use **Accept** or **Reject** in the **Review** panel, one by one or all at once.

## Passwords, PINs and your card

- When an action the assistant asks for needs a password, you type it into TEKSO's own window. TEKSO does not send it to the AI. The assistant only learns the outcome, for example done, wrong password or cancelled. The standalone server without the app has no such window and refuses the action.
- The assistant cannot sign for you and has no tool that takes your card PIN. Signing is always your action.
- **Fixed in 0.9.2:** in 0.9.1 the assistant could, through the text script tool (`text_script`), set, remove or check the password of a protected section in an `.odt` document with a password it supplied itself, without TEKSO asking you. Update to 0.9.2 or later.
- TEKSO cannot protect a password you write in the chat with the assistant, or one that is written in a document or file the assistant can read. Do not give passwords to the assistant.

What the assistant reads from a document you open to it, including a password-protected file after you have unlocked it, is sent to your AI provider and handled under its terms. Only share what you are comfortable sharing.

## Troubleshooting

- **The assistant says it has no access.** Check that **Allow Claude access** is on (for option B) or that the document is inside the folder you chose (option A).
- **It cannot save.** Read-only is on. Turn it off, or in the panel under **Claude read-only (cannot write files)**.
- **Connection lost after restarting TEKSO.** Restart the connection in Claude Desktop (option B).
- **Changed folder.** The allowed folder is chosen when the package is installed. To change it, reinstall the package and pick another folder.
- **A password window appears.** This is expected. Enter the password there yourself, not in the chat.
