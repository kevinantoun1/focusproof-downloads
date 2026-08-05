<div align="center">

<img
  src="https://www.focusproof.app/apple-touch-icon.png"
  width="96"
  height="96"
  alt="FocusProof app icon"
/>

# FocusProof Downloads

### Study normally. Then read the record.

A private, session-scoped study recorder for macOS.

[![Release](https://img.shields.io/badge/release-1.0.0-2f6f4e?style=flat-square)](https://www.focusproof.app/changelog)
[![Build](https://img.shields.io/badge/build-5-555555?style=flat-square)](https://www.focusproof.app/changelog)
[![macOS](https://img.shields.io/badge/macOS-15%2B-111111?style=flat-square&logo=apple)](https://www.focusproof.app/download)
[![Distribution](https://img.shields.io/badge/distribution-independent-b36b16?style=flat-square)](#independent-distribution)

[Website](https://www.focusproof.app) ·
[Download](https://kevinantoun1.github.io/focusproof-downloads/downloads/FocusProof-1.0.0.dmg) ·
[Chrome Companion](https://chromewebstore.google.com/detail/lmoghdnegapmpplnilnppdoanmmlnhpc) ·
[Privacy](https://www.focusproof.app/privacy) ·
[Support](https://www.focusproof.app/support)

</div>

---

## About FocusProof

FocusProof is a private Mac study recorder that creates an inspectable record of the study sessions you deliberately start.

Choose what you are studying, begin a Timer or Open-ended session, study normally on your Mac or away from it, then finish and review where the time went.

FocusProof is not a website blocker, AI coach, all-day activity monitor or institutional verification system. It is a personal record designed to help you understand your own study sessions.

## Current release

| | |
|---|---|
| **Version** | FocusProof 1.0.0 |
| **Build** | 5 |
| **Channel** | Stable |
| **Requires** | macOS 15 or later |
| **Mac support** | Apple silicon and Intel |
| **Price** | Free |
| **Account required** | No |
| **Distribution** | Independent and unnotarized |

### Download FocusProof

[**Download FocusProof 1.0.0 for macOS**](https://kevinantoun1.github.io/focusproof-downloads/downloads/FocusProof-1.0.0.dmg)

The published release is distributed as a macOS disk image.

For release information, see the [FocusProof changelog](https://www.focusproof.app/changelog).

## Installation

FocusProof is distributed independently and is not notarized by Apple. macOS therefore requires manual approval the first time you open it.

1. Download the FocusProof DMG.
2. Open the disk image.
3. Drag **FocusProof** into the **Applications** folder.
4. Try to open FocusProof from Applications.
5. Open **System Settings → Privacy & Security**.
6. Click **Open Anyway** next to FocusProof.
7. Confirm **Open**.

This is a one-time approval. Do not disable Gatekeeper or lower system-wide security settings.

A complete illustrated guide is available on the [download and installation page](https://www.focusproof.app/download).

## What FocusProof records

Recording occurs only while an eligible study session is running.

During a session, FocusProof may record:

- the active macOS application;
- supported Chrome website hostnames;
- activity timing and transitions;
- inactivity and unresolved periods;
- time you confirm as studying away from your Mac;
- pauses, breaks and user classifications.

FocusProof does not record:

- typed text or keystrokes;
- page contents;
- full URLs, paths or search queries;
- screenshots;
- private messages;
- clipboard contents;
- camera, microphone or location data;
- activity outside a running study session.

Your study data stays on your Mac unless you deliberately export or share it.

Read the full [FocusProof Privacy Policy](https://www.focusproof.app/privacy).

## Chrome companion extension

The optional FocusProof Chrome companion adds website-level detail to eligible study sessions.

Instead of recording only that Google Chrome was active, FocusProof can record the current website by hostname, such as `wikipedia.org`.

The extension:

- works only with the FocusProof Mac app;
- communicates locally through Chrome native messaging;
- sends website hostnames rather than full URLs;
- does not inspect page contents, searches or typed text;
- is not required for normal app-level recording.

[**Install the FocusProof Chrome companion**](https://chromewebstore.google.com/detail/lmoghdnegapmpplnilnppdoanmmlnhpc)

FocusProof remains fully usable for application-level recording, away study, Session Review, History, Insights and Study Receipts without the extension.

## Main features

### Deliberate sessions

Start a Timer or Open-ended session when you choose to study. FocusProof does not record continuously throughout the day.

### Computer and paper study

Record work performed on your Mac and explicitly confirm periods spent reading, handwriting or solving problems away from the computer.

### Session Review

Inspect Study Time, Focus Score, Score Coverage, activity classifications and the complete session timeline.

### Study Receipts

Create an optional Paper or Dark Study Receipt from the same calculations used by Session Review. Receipts are generated locally and exported only when you choose.

### History and Insights

Search previous sessions by subject or goal and review study patterns across time.

### Local backups

Create and restore local backups of your FocusProof data.

## Verify a download

Published checksums are available here:

[**FocusProof release checksums**](https://kevinantoun1.github.io/focusproof-downloads/updates/checksums.txt)

On macOS, calculate the SHA-256 checksum of a downloaded DMG with:

```bash
shasum -a 256 ~/Downloads/FocusProof-1.0.0.dmg
