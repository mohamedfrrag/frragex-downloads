# FrragEX Games downloads

Signed Android TV releases for FrragEX Games.

- Admin panel https://mohamedfrrag.github.io/frragex-admin/
- Android package local.retro.nestv
- Android 6.0 / API 23 or later with ARM 32-bit application support
- Version 1.11 has versionCode 15 and uses the same signing certificate as 1.9.

Use the direct APK asset link from Releases in Downloader on Android TV. Install it as an update to retain app data.

The app connects to hosted Supabase account services. The public Jumpcube catalogue is at
https://cstufywfjilztdnpnnvs.supabase.co/storage/v1/object/public/frragex-library/v1/library.json

A valid TV account is required. A successful online check allows offline use for up to 24 hours, bounded by subscription expiry. Administrators can disable an account, extend its subscription or unlink its device.

Emulator verification and physical-TV limits are described in each release.
Current APK https://github.com/mohamedfrrag/frragex-downloads/releases/download/v1.11/FrragEX-Games-v1.11.apk

Version 1.11 has Atari and PS1 tabs, a settings menu with update checks and sign-out, and update.json release metadata for versionCode comparison. APK updates are checked for package identity and the installed signing certificate before opening the Android installer.