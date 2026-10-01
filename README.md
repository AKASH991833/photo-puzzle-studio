# Frame Jigsaw

Photo jigsaw game with a wooden table, interlocking pieces, and a full tray. Pick any loose piece in any order. No forced sequence or tray pages. Built-in photos and custom photo uploads stay on the device.

Live browser game: https://akash991833.github.io/photo-puzzle-studio/

## Android

Capacitor Android app: `com.akash.photopuzzle`, Frame Jigsaw, v1.1 (versionCode 2), Android 7+.

```
npm ci
cp index.html www/index.html
npx cap sync android
cd android
./gradlew assembleRelease
```

Use JDK 21 and Android SDK 36. Sign the resulting unsigned APK with the game's existing owner-held key for updates. Never commit the key or passwords. The encrypted signing-key backup is private in the owner's Drive, and its password is stored separately in the secure vault.

The app includes all game assets and does not request Internet access. Image upload uses Android's system file picker. Device installation and file-picker behavior should be verified on a phone before broader distribution.
