# Lumen TV — APK downloads

Public APK and OTA channel for Lumen TV on Android TV 11+. Application source and history remain private. This repository contains distribution documentation only.

- [Download Lumen TV 1.5.1 APK](https://github.com/onchainwendy/lumen-android-tv/releases/download/v1.5.1/Lumen-TV-1.5.1-debug.apk)
- [Latest release notes and checksums](https://github.com/onchainwendy/lumen-android-tv/releases/latest)

Current version: **1.5.1**, versionCode **16**, package `com.lumen.tv`. Development-signed sideload build; same signing certificate as 1.5.0. In Lumen: **Settings → Options → Software update**.

## Changes

Launcher-level app lock: hold OK on a Home tile and choose Lock app; locked tiles show a badge and opening one asks for a 4-digit code, with the hold-OK menu opening beside the tile. The code is the current TV clock time HHmm reversed (14:45 → 5441) and is not shown in the UI; a wrong code clears the digits and keeps the glass passcode panel open. This is a child lock for launcher launches (rows, dock/More apps, Recent, folders), not OS-level security. The old Add to Games / Media / Tools presets are removed; unlocked apps offer Move / Remove from Home / Lock app. Also includes liquid-glass light/dark surfaces and Home opacity recovery.

Build verification: 53/53 browser tests, type-check, webOS and Android frontend builds and Android debug build/lint pass. The flow was exercised on a development TV with injected keys; physical-remote confirmation is still pending.

APK SHA-256:

```text
a8c7f3a45e6aa832eb59af5a87b7f255058c98c15776c1fa9cd4f222101bc257
```

GitHub-generated source archives contain only distribution documentation, not application source. Third-party license notices are bundled in the APK.
