# Production Floor for Android

The Android app for Production Floor. Employees use it on their own phones to start work at a
station by scanning its QR code, record finished units, pause and end work. Managers see who is
working on each floor.

This repository only holds the app's downloads. The source code is private.

## Download

**[Download the latest version (production-floor.apk)](https://github.com/ksongProjects/production-floor-android/releases/latest/download/production-floor.apk)**

You can also open the Production Floor sign-in page on your computer, select
**Get the Android app**, and scan the QR code with your phone.

All versions are listed under [Releases](https://github.com/ksongProjects/production-floor-android/releases).

## Requirements

- Android 7.0 or newer
- A Production Floor login from your company (the same email and password as the website)
- An internet connection while you work

An iPhone version is planned.

## Install

1. Open the download link on your phone. The file is about 90 MB.
2. Open the downloaded file. If Android asks, allow your browser to **install unknown apps**.
   You only need to do this once.
3. If Google Play Protect warns that the app is unknown, select **More details** and then
   **Install anyway**. This warning appears for apps that are not installed from the Play Store.
4. Open **Production Floor** and sign in with your work email and password.

## Using the app

- **Start work:** select **Scan station** and point the camera at the QR code on your station.
  Work starts on the station's current task.
- **While working:** record finished units with **+1**, **+5** or **+10**. Use **Pause** for
  breaks and **Resume** to carry on.
- **End work:** select **End work** and say whether the task is finished.
- **Managers** see each floor they manage, with who is working, on what, and how many units are
  done.

If the app says you have no work access, ask your manager to add you to a floor.

## Permissions

- **Camera:** only to scan station QR codes. The app takes no photos or videos.
- **Internet:** to talk to your company's Production Floor server.

## Updates

The app does not update itself yet. When a new version is released:

1. Download it from the link above.
2. Install it over the existing app. You stay signed in, and nothing is lost.

Android only installs a new version if it is newer than the one on the phone and signed with the
same key.

## Check that a download is genuine

Every version is signed with the same key. Its certificate SHA-256 fingerprint is:

```
a668945657853514e93a4e9cc2fbc322702de3b680adc61db0903f99348a0f98
```

With the Android SDK build tools installed, compare it with the `certificate SHA-256 digest` line
from:

```
apksigner verify --print-certs production-floor.apk
```

## Help

For sign-in problems, access to floors, or questions about your work, contact your manager or your
company's Production Floor administrator.
