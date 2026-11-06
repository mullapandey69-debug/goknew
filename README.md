<div align="center">

# Bytes Music

**Your music, your library, your sound.**

A community-maintained Bytes Music rebrand of the open-source Musify Flutter application.

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](LICENSE)

</div>

---

## About

Bytes Music is a music player built on the Musify open-source Flutter project. This repository contains the Bytes Music-branded fork, including the Android application ID `com.bytesmusic.app`.

The upstream project and its contributors retain their original copyright and attribution. Bytes Music branding and fork-specific changes do not imply endorsement by the upstream authors.

## Build the Android APK

Requirements: Flutter SDK compatible with the version in `pubspec.yaml`, Android SDK, and Java 17.

```bash
flutter pub get
flutter build apk --debug --flavor github
```

The debug APK is generated at:

`build/app/outputs/flutter-apk/app-github-debug.apk`

You can also build it on GitHub without installing Flutter locally:

1. Open the repository's **Actions** tab.
2. Select **Build Bytes Music APK**.
3. Click **Run workflow**.
4. When it finishes, open the run and download the `BytesMusic-debug-apk` artifact.

The CI debug build uses Android's debug signing key and is intended for testing, not Play Store publishing.

## Upstream project and attribution

This project is a modified fork of [Musify by Valeri Gokadze](https://github.com/gokadzev/Musify). The original project is licensed under the GNU General Public License v3.0. Original copyright notices and the full `LICENSE` are retained. Changes in this fork must remain available under GPL-3.0 when distributed.

## Disclaimer

Bytes Music does not claim ownership of music, recordings, artwork, or other third-party content accessed through the application. Users must follow applicable laws and the terms of the services they use.

---
