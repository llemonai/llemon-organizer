# llemonAI PDF Organizer

A free PDF organizer for **Windows** and **Android**, from [llemonai](https://llemonai.in).

- **Website:** https://llemonai.in/organizer.html
- **Download:** https://llemonai.in/organizer.html#download
- **Latest release:** https://github.com/llemonai/llemon-organizer/releases/latest

## Page-by-page resolution

Typical PDF compressors squeeze the whole file at one setting, so text pages get blurry just to
shrink a few photos. llemonAI PDF Organizer lets you choose the resolution **for each page**:
select the pages that make the file big, usually photos and scans (every thumbnail shows its
share of the file size), and shrink only those. Text pages stay sharp and searchable.

The dialog shows each page's size before and after, warns you when a picture would be larger
than the page already is (ordinary text pages), and by default leaves such pages unchanged.

## What else it does

- **File size on the main screen:** original size, size after your changes, and every page's share.
- **Pages:** drag to reorder, rotate, add blank pages, delete; select several pages at once; undo and redo.
- **Combine files:** append or insert PDF, Word (.docx and Word 97–2003 .doc) and text (.txt) files.
  Text in Indian and other scripts shows correctly.
- **Page numbers:** add them to all pages (position, format such as "Page 1 of 10", start number,
  skip the cover), or find and delete the numbers already printed in a document.
- **Print** the document as it will be saved.
- **Privacy:** works offline; documents never leave your device.

## Requirements

| Platform | Requirement |
|---|---|
| Windows | Windows 10 or 11, 64-bit or 32-bit. It's a single portable `.exe` with no installer and no admin rights, and it uses the Microsoft Edge WebView2 runtime built into Windows. |
| Android | Android 8.0 (API 26) or later, as a sideloaded `.apk`. |

## Verifying downloads

The builds are signed with llemonai's own self-signed certificate (Windows) and release key
(Android). Windows SmartScreen may show "Unknown Publisher" and Android may warn about an unknown
source; both are expected.

To confirm a file is genuine, compare its SHA256 checksum. On Windows, run `certutil -hashfile <file> SHA256`.

| File (v1.5.0) | SHA256 |
|---|---|
| `llemonAI-PDF-Organizer-1.5.0-android.apk` | `EDE72F41A09D5A2917A6781D4DA79A5B4E094E0707C04371EC285EFB251CA18C` |
| `llemonAI-PDF-Organizer-1.5.0-win-x64.exe` | `B1D2BC325F40C1780AA1D77BDDE5715F4F47B19216487A0CC3D5E45ECB2C9328` |
| `llemonAI-PDF-Organizer-1.5.0-win-x86.exe` | `DD8AE4286C7C04AF32385D3C47258B14CA88461B0AC3EC66BA44468CD832D251` |

## Repo contents

This repository holds only the release binaries and this README. The application source code is not public.

Third-party open-source components are listed in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## Contact

llemonai.us@gmail.com

&copy; 2026 llemonAI (llemonai.in). All rights reserved.
