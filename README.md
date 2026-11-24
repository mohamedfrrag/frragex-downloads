# FrragEX Games downloads

Signed Android TV releases for FrragEX Games.

- [Current APK 1.12 — direct download](https://github.com/mohamedfrrag/frragex-downloads/releases/download/v1.12/FrragEX-Games-v1.12.apk)
- [Release notes and source/license asset](https://github.com/mohamedfrrag/frragex-downloads/releases/tag/v1.12)
- [FrragEX Admin](https://mohamedfrrag.github.io/frragex-admin/)
- Package `local.retro.nestv`; versionCode 16; same signing certificate as 1.9–1.11.
- Android 6.0 / API 23 or later, with ARM 32-bit application support.

Use the direct APK link in Downloader on Android TV. Install as an update to retain data. APK size: 79,470,265 bytes (75.79 MiB).

Three independent system tabs: NES (default), Atari 2600, PS1. 800 NES cartridges are bundled, including 39 explicitly marked as requiring more emulator support; 595 Atari 2600 cartridges are bundled. No PS1 discs are embedded. Import your own CHD/BIN/CUE, or configure your own HTTPS library index in the PS1 tab. Existing user imports/downloads remain. There is no automatic game deletion or old Jumpcube catalogue fetch.

The app connects to hosted Supabase account services and does not require a running PC. A valid TV account is required. Offline access is up to 24 hours, bounded by subscription expiry. Administrators can disable an account, extend its subscription or unlink its device.

The app checks GitHub Releases and the attached update.json. APK updates are verified for SHA-256, package identity, versionCode and the installed signing certificate before opening Android's installer.

Android emulator verification includes update/data retention, sample games, offline access, sign-out and synthetic analog input. Physical TV/gamepad tests and full-game compatibility remain device-dependent. See each release's test limits. Stella2014 source/license is supplied separately; private admin/account source and signing keys are not stored in this repository.
