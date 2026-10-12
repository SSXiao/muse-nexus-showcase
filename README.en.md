# Muse Nexus · Desktop Developer Tools

**Inline Markdown preview, an SSH / SFTP client, API debugging, database queries, and everyday data utilities.**

[Website & Download](https://lingban.xyz/) · [简体中文](README.md) · [Markdown guide (Chinese)](docs/markdown.md) · [SSH / SFTP guide (Chinese)](docs/ssh-sftp.md) · [Feedback](https://github.com/SSXiao/muse-nexus-showcase/issues)

Muse Nexus brings documentation, API debugging, database work, and remote file management into one desktop toolkit. Tools open in individual windows, so you can keep a document beside an API request or inspect a terminal alongside remote files.

This repository provides public product information, usage guides, and a place to report issues. Visit the [website](https://lingban.xyz/) for installers and current platform availability.

## Markdown that renders where you write

In the editable reading view, the current line exposes its Markdown syntax. Move the cursor to another line—or press Enter—and the previous line renders in place. Return to that line to edit the syntax again.

| Edit the current line | Move away to see the result |
| --- | --- |
| ![Markdown code and bold delimiters visible on the active line](assets/markdown-editing.jpg) | ![The previous line renders inline code and bold text](assets/markdown-preview.jpg) |

For tables, fenced code, Mermaid diagrams, and display math, edit the complete block and move the cursor outside it to see the rendered result.

Use headings and an outline to organize READMEs, API documentation, or technical notes. Add code blocks, tables, task lists, Mermaid diagrams, and KaTeX formulas. Save Markdown files, export HTML, or use system printing to produce a PDF. Focus mode, typewriter mode, and appearance themes help configure your writing environment.

## SSH / SFTP is available now

Save connection profiles, open sessions in separate tabs, and switch between a terminal, local / remote file browsing, and terminal / remote split view.

![SSH terminal and remote log directory shown side by side](assets/ssh-terminal-split.jpg)

- Password, Ed25519 / RSA key, and encrypted private-key authentication.
- Host fingerprint confirmation before first authentication; changed saved host keys block the connection.
- File and folder uploads and downloads, with transfer progress and explicit conflict handling.
- Direct connections to your SSH host; the Muse Nexus account service does not relay SSH traffic.

Current boundaries include no jump-host support, SSH agent, port forwarding, remote editing, or transfer resume. See the [SSH / SFTP guide](docs/ssh-sftp.md) for the workflow and limitations.

## The toolkit

| Tool | Capabilities |
| --- | --- |
| API client | Request collections, environment variables, multipart requests, OpenAPI import |
| Database | MySQL and SQLite connections, SQL queries, data browsing, result export |
| Network capture | Local proxy, HTTP / HTTPS inspection, send requests to the API tool |
| JSON / YAML | Formatting, validation, structured browsing, file open and save |
| Developer utilities | JWT decoding, Base64 / URL encoding, image Base64, timestamps, hashes, UUIDs |

The interface supports Simplified Chinese and English, with light, dark, and landscape themes.

## Get started

1. Visit [lingban.xyz](https://lingban.xyz/) to download an installer for your system.
2. Start Muse Nexus and select a tool in the tool center.
3. Use [Issues](https://github.com/SSXiao/muse-nexus-showcase/issues) for product feedback or documentation corrections. Include your app version, operating system, and steps to reproduce the issue.

Screenshots contain demonstration hosts, logs, and API data. Markdown screenshots show the browser development preview; SSH screenshots use demo data to illustrate the interface. Real SSH sessions and desktop file operations require the installed application.

This is a public product-information repository. It does not contain the application or server source code. Product names, marks, and application rights belong to their respective owners.
