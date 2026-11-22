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
- **Combine files:** append or insert PDF, Word (.docx and Word 97–2003 .doc) and text (.txt) files, and pictures: JPEG, PNG, GIF, WebP, BMP, AVIF, TIFF and HEIC/HEIF photos from an iPhone, iPad or Mac, one page each.
- **Large files:** scanned files of a gigabyte or more open and save, with a progress bar.
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
| macOS | macOS 12 or later, Apple Silicon or Intel. Open the `.dmg` and drag the app to Applications. It isn't notarized by Apple, so the first time allow it in **System Settings → Privacy & Security → Open Anyway** ([steps](https://llemonai.in/organizer.html#mac-open)). |
| Android | Android 8.0 (API 26) or later, as a sideloaded `.apk`. |

## Verifying downloads

The builds are signed with llemonai's own self-signed certificate (Windows), release key
(Android) and an ad-hoc signature (macOS). Windows SmartScreen may show "Unknown Publisher",
Android may warn about an unknown source, and macOS blocks the first launch until you click Open Anyway in Privacy & Security; all are expected.

To confirm a file is genuine, compare its SHA256 checksum. On Windows, run `certutil -hashfile <file> SHA256`; on a Mac, `shasum -a 256 <file>`.

| File (v1.6.0) | SHA256 |
|---|---|
| `llemonAI-PDF-Organizer-1.6.0-android.apk` | `9AE824CB8E06110225B5E0D396E56F8C34496DD2D1FED03BE5BE3E704189978D` |
| `llemonAI-PDF-Organizer-1.6.0-macos.dmg` | `902FFE2475B2E054673BFA32895EC62324316FC1F020AA50C56DB546629F3254` |
| `llemonAI-PDF-Organizer-1.6.0-macos.zip` | `740DEB867EBBC777B74D7861D849AD85E71E8120E77134D7663A8FF504F872DE` |
| `llemonAI-PDF-Organizer-1.6.0-win-x64.exe` | `E8BF8B6FD051FAAF756874B048A2EAEF2B4901A6CF4FE1252B7FA903C1158A7C` |
| `llemonAI-PDF-Organizer-1.6.0-win-x86.exe` | `CE79BF6814C55483FAA5F0E5E2A99A93E24FCCA67F842514DA842074F33040C9` |

## Repo contents

This repository holds only the release binaries and this README. The application source code is not public.

Third-party open-source components are listed in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## Contact

llemonai.us@gmail.com

&copy; 2026 llemonAI (llemonai.in). All rights reserved.
