# openGym Android

<div align="center">

<img src="assets/banner.png" alt="openGym" width="720">

<br>
> An unofficial Android build of [openGym](https://github.com/DuarteSantos8/openGym), published to make the Android app easier to download and install.

[![License: AGPL v3](https://img.shields.io/badge/license-AGPL--3.0-blue.svg)](LICENSE)
[![Android](https://img.shields.io/badge/platform-Android-green.svg)](https://www.android.com/)
[![APK](https://img.shields.io/badge/download-APK-orange.svg)](#download)


> [!NOTE]
> **The official openGym project is available again.**
>
> Official website: https://opengym.duarte-santos.ch/
>
> This repository remains an **unofficial community Android build** that provides the Android source and signed APK, while all credit belongs to the original openGym project.

## About

[openGym](https://github.com/DuarteSantos8/openGym) is a self-hosted gym and body-weight tracker designed around ownership of your workout data. It includes features such as weekly workout planning, guided workouts, exercise tracking, progression, body-weight tracking, statistics, and more. The original project also provides web, iOS/PWA, and Android experiences.
This repository contains the **Android portion** of the project so that users who only want the Android app can easily access the source and a downloadable APK.


## Why this repository exists

The original project's downloadable Android release became difficult to access because the APK/release was unavailable.

I created this repository to make the Android build easier for the community to obtain:

* The Android source is available here on GitHub.
* A signed APK is published through GitHub Releases.
* The APK has been tested on a physical Android device.
* The project remains open source under the same AGPL-3.0 license.

This is **not an attempt to replace or claim ownership of openGym**. It is a community-maintained Android build based on the original project.

## Download
<br>

<div align="center">
<table>
<tr>
<td align="center"><img src="assets/screenshots/home.png" alt="Home" width="230"><br><sub><b>Home</b> — today's workout & weight</sub></td>
<td align="center"><img src="assets/screenshots/workout.png" alt="Workout" width="230"><br><sub><b>Guided workout</b> — animated demos & sets</sub></td>
<td align="center"><img src="assets/screenshots/stats.png" alt="Stats" width="230"><br><sub><b>Stats</b> — heatmap, charts & PRs</sub></td>
</tr>
</table>
</div>
### Android APK

Download the latest **signed APK** from the [Releases](../../releases) page.

> Android may warn you when installing an APK downloaded outside Google Play. You may need to allow installation from your browser or file manager.

## Installation

1. Download the latest APK from [Releases](../../releases).
2. Open the APK on your Android device.
3. Allow installation from the source you used to download the APK if Android asks.
4. Install and launch openGym.

## Source

This repository publishes the Android project contained in the original openGym codebase.

The Android project has only been minimally modified for release purposes. The primary change made in this repository is the Android release signing configuration in `app/build.gradle`, allowing a signed APK to be generated and distributed.

No private signing keys or passwords are included in this repository.

## Testing

The published release APK has been installed and tested on a physical Android device.

The purpose of this repository is primarily to provide a readily downloadable Android build of openGym; it is not intended to represent a major rewrite or independent implementation of the application.

## Attribution

This project is based on **openGym**.

Original project:

**Duarte Santos / openGym**
https://github.com/DuarteSantos8/openGym

Related original repository/reference:

**arvids-unavailable/openGym**
https://github.com/arvids-unavailable/openGym

The original project and its authors retain credit for the original application, design, functionality, and code.

This repository is an **unofficial community Android build** and is not presented as the official openGym repository.

## License

This repository is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**.

See [LICENSE](LICENSE) for the full license text.

Because this project is based on AGPL-licensed openGym code, the corresponding source remains available under the same license.

## Disclaimer

This repository is maintained independently and is not affiliated with, endorsed by, or officially maintained by the original openGym authors.

Use the APK at your own discretion and verify the release/source before installation.

## Contributing

Issues and pull requests are welcome for Android-specific fixes, build improvements, documentation, and other changes that help make the Android build easier to use.

Please keep contributions compatible with the project's AGPL-3.0 licensing.

---

### Original project

🌐 **openGym:** https://github.com/DuarteSantos8/openGym

### This repository

📱 **openGym Android:** https://github.com/ssprasad-cyber/opengym-android
