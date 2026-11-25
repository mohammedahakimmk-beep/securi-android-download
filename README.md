# Securi Android downloads

This repository contains public Android test downloads only. It does not contain the app source or Firebase client configuration.

## Current build: 0.5.0 debug preview

- Android package: `com.securi.app`
- Android 8.0 (API 26) or newer
- [Download the APK](https://github.com/mohammedahakimmk-beep/securi-android-download/releases/download/v0.5.0/securi-android-debug.apk)
- SHA-256: `708bc119a3f65eebfaaf9783a0cbd991e71cb8f68ca888558e8637d31b0ff0d9`
- Verify with `shasum -a 256 -c securi-android-debug.apk.sha256`.

This preview includes one-time remote location sharing after the phone owner approves a request; cloud event labels; nearby offline pairing with a verification code and an explicit send action; and remote screen lock after the owner enables Android device-admin access. Location reads expire after five minutes. The owner or recipient can delete shared coordinates earlier.

FCM token registration and the Firebase sender function are prepared, but the function is not deployed. Automated push alerts therefore are not active. Deploying Cloud Functions requires enabling Firebase billing. Brightness control is not included.

The APK is debug-signed and is not a Play Store release. Two-phone end-to-end tests have not been completed. Remote Firebase features need verified accounts, an accepted invite, owner-enabled visible monitoring, and internet. Nearby exchange requires both phones within range with permissions granted. Do not rely on this preview as an emergency recovery service.
