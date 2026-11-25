# Securi Android downloads

This repository contains public Android test downloads for Securi. It contains no app source code or Firebase client configuration.

## Current build

- Version: 0.2.0 debug preview
- Package: `com.securi.app`
- Android 8.0 (API 26) or newer
- [Download the APK](https://github.com/mohammedahakimmk-beep/securi-android-download/releases/download/v0.2.0/securi-android-debug.apk)
- SHA-256: `10f46714756ef63a8ba1980beaa05b77b1b48255bfd930e90a501ff77fc69d84`
- Verify after downloading both release assets with `shasum -a 256 -c securi-android-debug.apk.sha256`.

This is a debug-signed test build, not a store release. Remote alarm requests require an owner-enabled visible monitor, an accepted invite, verified Firebase email accounts, and internet access. The app has not been tested on a physical Android phone and should not be relied on as an emergency recovery service.
