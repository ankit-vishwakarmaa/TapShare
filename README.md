# TapShare

NFC tap-to-share for Android (Samsung-friendly). Hold two NFC phones together to share a photo or file.

## Download APK

**Latest debug APK:**
https://github.com/ankit-vishwakarmaa/TapShare/releases/latest/download/TapShare-debug.apk

If the release is still publishing, check the [Releases](https://github.com/ankit-vishwakarmaa/TapShare/releases) page.

## Install

1. Allow install from unknown sources for your browser/file manager.
2. Install `TapShare-debug.apk` on **both** phones.
3. Receiver: open TapShare → **Ready to receive**.
4. Sender: **Send a file** → pick a file → hold phones together.

## Build from source

Clone this repo (or the linked project) and run:

```bash
./gradlew :app:assembleDebug
```

Requires Android SDK 35 and JDK 17+.
