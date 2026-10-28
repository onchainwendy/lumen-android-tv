# Lumen TV — APK downloads

Public APK and OTA channel for Lumen TV on Android TV 11+. Application source and history remain private. This repository contains distribution documentation only.

- [Download Lumen TV 1.5.0 APK](https://github.com/onchainwendy/lumen-android-tv/releases/download/v1.5.0/Lumen-TV-1.5.0-debug.apk)
- [Latest release notes and checksums](https://github.com/onchainwendy/lumen-android-tv/releases/latest)

Current version: **1.5.0**, versionCode **15**, package `com.lumen.tv`. Development-signed sideload build; same signing certificate as 1.4.9. In Lumen: **Settings → Options → Software update**.

## Changes

One-shot native voice control for VTVgo/GetOut/YouTube, host voice-key fallback, and Wi-Fi SSID permission request. Voice routing depends on firmware: microphone permission alone may not redirect the remote key. Keep the TV recognition service (Google/Katniss where applicable) enabled; no package disabling is required. Owner configuration may be needed.

Build verification: 34 JVM tests, 43 browser tests, frontend builds/type-check and Android debug build/lint pass. Actual spoken commands and overlay reset after assistant rerouting are still awaiting confirmation on the development TV.

APK SHA-256:

```text
18e136ef059eaa622d51631aae0bac8430867c71f283e2de3cf0e32b3e9b030e
```

GitHub-generated source archives contain only distribution documentation, not application source. Third-party license notices are bundled in the APK.
