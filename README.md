# Petal Key

Offline English-US Android keyboard for Android10 and newer. It works inside existing messaging and other apps. Optional voice typing uses Android's on-device recognizer only; live provider accuracy and lifecycle are not qualified by the current emulator tests. No Internet permission, analytics, advertising, cloud inference or automatic typed-text persistence.

Download the APK and full corresponding source ZIP from [Releases](https://github.com/ClownChowder/petal-key/releases). This repository indexes personal preview releases; GitHub's automatic source archives are not the app source. Use the explicitly attached `petal-key-source.zip`. Upstream copyright notices and licenses remain in the source and app assets.

The current release is **0.1.23-preview (version code24)**. It fixes key-preview lifecycle retention, invisible reused previews and duplicate-parent failures. See the attached `CHECKS.txt` for verification, inherited warnings and qualification limits.

Verified:30 JVM tests,97 Android17/API37 integration tests and21 selected Android10/API29 tests. Physical-phone, live speech, live TalkBack/Switch Access, Android15/16 runtime and native sanitizer checks were not rerun for this APK. ARM32 device testing is excluded at the user's request.

## Obtainium

Source: `https://github.com/ClownChowder/petal-key`

APK filename filter: `^petal-key\.apk$`

Android package: `app.petalkey.inputmethod.latin`

Signing certificate SHA-256: `386f097ea7de3749f0b0cc87e433d0f8a8a70cebb1848d7e7cb4bd5f60cff2b4`

The signing identity matches the previous published preview. These are debug-signed personal previews, not production-signed store releases. Obtainium detects published releases; it does not develop or build new versions. Signing keys, saved API keys, pairing tokens and personal app data are not published. Checksums are attached to each release.

## Original authors and credits

See [CREDITS.txt](CREDITS.txt) for original authors, upstream projects, recording/model creators and applicable licenses. Original license and copyright notices remain in the corresponding source archives and app assets. No upstream endorsement is implied.
