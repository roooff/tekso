# AI and MCP

[Български](bg/ai-and-mcp.md) · [Docs index](README.md)

MCP (Model Context Protocol) is an open standard that lets an AI assistant such as Claude work with tools on your computer. With TEKSO it means the assistant can read your documents and suggest edits. The AI part is **off by default**. TEKSO works fully without it.

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

Turn read-only off only if you want the assistant to save changes to files in that folder.

**B. The documents open in TEKSO.** Install the same `.mcpb` package and turn on **Work in the open TEKSO window** in its settings in Claude Desktop. Then, in TEKSO, turn on **Allow Claude access** as above (and add folders in **Settings > Claude** if Claude should open files itself). You and the assistant then work on the same open document, with one shared Undo, and every change appears as a proposal. TEKSO must be open while you work this way.

## How proposals work

The assistant can read and draft, but every change is a proposal. Nothing is applied until you accept it. If you reject a proposal, nothing happens. Always review before accepting: AI suggestions can be wrong.

In the Claude panel you can:

- see who is connected and a **Log of calls on this document**;
- turn on **Claude read-only (cannot write files)**;
- click **Stop Claude** to turn access off at once;
- click **Undo everything from Claude** or **Revert everything** to go back.

In text documents the proposals appear as tracked changes. Use **Accept** or **Reject** in the **Review** panel, one by one or all at once.

## What never reaches the AI

- Passwords and PINs. They are typed only into TEKSO's own window. The assistant only learns whether it worked.
- Your smart card and its keys. The assistant cannot sign for you. Signing is always your action.

Everything else in a document you open to the assistant is sent to your AI provider and handled under its terms. Only share what you are comfortable sharing.

## Troubleshooting

- **The assistant says it has no access.** Check that **Allow Claude access** is on (for option B) or that the document is inside the folder you chose (option A).
- **It cannot save.** Read-only is on. Turn it off, or in the panel under **Claude read-only (cannot write files)**.
- **Connection lost after restarting TEKSO.** Restart the connection in Claude Desktop (option B).
- **Changed folder.** The allowed folder is chosen when the package is installed. To change it, reinstall the package and pick another folder.
- **A password or PIN window appears.** This is expected. Enter it there yourself.
