# llemonAI PDF Organizer

A free PDF organizer for **Windows**, **macOS** and **Android**, from [llemonai](https://llemonai.in).

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
- **Updates:** About → Check for updates downloads a newer release, checks its SHA-256 checksum and installs it. Nothing is checked unless you click it.

## Requirements

| Platform | Requirement |
|---|---|
| Windows | Windows 10 or 11, 64-bit or 32-bit. It's a single portable `.exe` with no installer and no admin rights, and it uses the Microsoft Edge WebView2 runtime built into Windows. |
| macOS | macOS 12 or later, Apple Silicon or Intel. Open the `.dmg` and drag the app to Applications. It isn't notarized by Apple, so the first time, right-click it and choose **Open**. |
| Android | Android 8.0 (API 26) or later, as a sideloaded `.apk`. |

## Verifying downloads

The builds are signed with llemonai's own self-signed certificate (Windows), release key
(Android) and an ad-hoc signature (macOS). Windows SmartScreen may show "Unknown Publisher",
Android may warn about an unknown source, and macOS asks you to confirm the first launch; all are expected.

To confirm a file is genuine, compare its SHA256 checksum. On Windows, run `certutil -hashfile <file> SHA256`; on a Mac, `shasum -a 256 <file>`.

| File (v1.5.1) | SHA256 |
|---|---|
| `llemonAI-PDF-Organizer-1.5.1-android.apk` | `A3DD1E01803BEB14764FC1E68E84BF7F4D1F951366D3DA88A01F6C4842CAB153` |
| `llemonAI-PDF-Organizer-1.5.1-macos.dmg` | `C01A0BAB696C092BE356BDC55F43D9F46D8D8F6732808BB7EDDF074472742233` |
| `llemonAI-PDF-Organizer-1.5.1-macos.zip` | `78B0209511CE48264E75444BA50746FAD326913AAB7595F15E9A9B747B5781DB` |
| `llemonAI-PDF-Organizer-1.5.1-win-x64.exe` | `5D32B67F187908849D9FA02B1D7B334AD997354B2D33A50EC13FD46B6E4FD111` |
| `llemonAI-PDF-Organizer-1.5.1-win-x86.exe` | `2E2C320EFE948C061A424A3580EDEC085F2E0305BE9562AB6C692A5394F70292` |

## Repo contents

This repository holds only the release binaries and this README. The application source code is not public.

Third-party open-source components are listed in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## Contact

llemonai.us@gmail.com

&copy; 2026 llemonAI (llemonai.in). All rights reserved.
