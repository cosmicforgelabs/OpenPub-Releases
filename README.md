# OpenPub

OpenPub opens Microsoft Publisher (`.pub`) files on Windows. You can look at them, print them, and save
them as a PDF or a Word document — without Publisher, and without installing anything else.

Microsoft retires Publisher on 1 October 2026. OpenPub exists so the files people already have stay
usable afterwards. More at **[cosmicforgelabs.com/openpub](https://cosmicforgelabs.com/openpub)**.

## Download

**[Download OpenPub](https://github.com/cosmicforgelabs/OpenPub-Releases/releases/latest/download/OpenPub.exe)**

One file. No installer, no administrator rights. Save it somewhere handy and double-click it.
Needs Windows 10 version 1903 (May 2019) or newer, 64-bit.
All versions are listed under [Releases](https://github.com/cosmicforgelabs/OpenPub-Releases/releases).

## What it does

- **Open** a Publisher file: drag it onto the window, double-click it, or use the Open button.
- **View** the pages as they were designed, with thumbnails, zoom, and facing pages side by side.
- **Print.**
- **Save as PDF** — the pages exactly as shown, for keeping, sharing and printing.
- **Save as Word** — an editable Word document that keeps the layout: the same pages, the text boxes and
  pictures where they were, and web and email addresses you can click.
- **Convert whole folders** to PDF or Word, choosing exactly which files.
- **Keeps itself up to date**, installing new versions when you close it.

OpenPub tells you plainly when something may look different from the original: a font that isn't on the
computer, or clip art it can't draw.

## Signed by Embermont Ltd

From version 1.1.0, OpenPub is code-signed. Windows shows **Embermont Ltd** as the verified publisher,
and OpenPub only installs updates that carry that same signature. (Versions up to 1.0.9 were not signed;
they update to 1.1.0 by themselves.)

## Your files stay with you

Publisher files are read inside an isolated sandbox that has no access to your documents and no access to
the internet. Nothing you open is uploaded anywhere. The only thing OpenPub sends over the internet is a
check for a newer version.

## Open-source components

OpenPub reads Publisher files using **libmspub** and **librevenge**, open-source libraries under the
Mozilla Public License 2.0, together with zlib and Boost, and the ICU text library built into Windows.

As the MPL requires, the source of those libraries — including OpenPub's own fixes to them — is attached
to every release as `openpub-source-v<version>.zip`. The licence texts are inside the app, under
**?** → **Licences folder**.

## About this repository

This repository holds the published downloads only. OpenPub's own source code is not published here.
For help and support, visit [cosmicforgelabs.com/openpub](https://cosmicforgelabs.com/openpub).

OpenPub is made by CosmicForge Labs and published by Embermont Ltd, registered in England and Wales.
Microsoft and Microsoft Publisher are trademarks of the Microsoft group of companies. OpenPub is not
affiliated with or endorsed by Microsoft.
