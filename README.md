# OpenPub

OpenPub opens Microsoft Publisher (`.pub`) files on Windows. You can look at them, print them, and save
them as a PDF or a Word document — without Publisher, and without installing anything else.

Microsoft is retiring Publisher in October 2026. OpenPub exists so the files people already have stay
usable afterwards.

## Download

**[Download OpenPub](https://github.com/cosmicforgelabs/OpenPub-Releases/releases/latest/download/OpenPub.exe)**

One file. No installer, no administrator rights. Save it somewhere handy and double-click it.
All versions are listed under [Releases](https://github.com/cosmicforgelabs/OpenPub-Releases/releases).

## What it does

- **Open** a Publisher file: drag it onto the window, or use the Open button.
- **View** the pages as they were designed, with page thumbnails and zoom.
- **Print.**
- **Save as PDF** — the pages exactly as shown, for keeping, sharing and printing.
- **Save as Word** — the text and pictures, so you can edit them in Word.
- **Convert several at once**: drop a batch of files in and they all become PDFs.
- **Keeps itself up to date** in the background.

OpenPub tells you plainly when something may look different from the original: a font that isn't on the
computer, or clip art it can't draw yet.

## The first time you run it

Windows may show a blue "Windows protected your PC" message, because this app is new and not yet
code-signed. Click **More info**, then **Run anyway**. This will stop once code signing is in place.

## Your files stay with you

Publisher files are read inside an isolated sandbox that has no access to your documents and no access to
the internet. Nothing you open is uploaded anywhere. The only thing OpenPub sends over the internet is a
check for a newer version.

## Open-source components

OpenPub reads Publisher files using **libmspub** and **librevenge**, open-source libraries under the
Mozilla Public License 2.0, together with ICU, zlib and Boost.

As the MPL requires, the source of those libraries — including OpenPub's own fixes to them — is attached
to every release as `openpub-source-v<version>.zip`. The licence texts are inside the app, under
**?** → **Open licences folder**.

## About this repository

This repository holds the published downloads only. OpenPub's own source code is not published here.

Microsoft and Microsoft Publisher are trademarks of the Microsoft group of companies. OpenPub is not
affiliated with or endorsed by Microsoft.
