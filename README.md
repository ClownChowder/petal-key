# Petal Key

Offline English-US Android keyboard for Android 10 and newer. Works inside existing messaging and other apps. Optional voice typing uses Android's on-device recognizer only. No INTERNET permission, analytics, advertising, cloud inference or automatic typed-text persistence.

Current personal preview: **0.1.26-preview (version code 27)**. Adds **Typing → Popup letters on keypress** and enables preview control at every screen size. Existing saved choices are preserved; if previews were off, turn the switch on. Password and other protected fields still hide previews. Long-press alternatives are separate.

Download `petal-key.apk` from [the verified preview](https://github.com/ClownChowder/petal-key/releases/tag/v0.1.26-preview). The complete corresponding source, tests, Gradle wrapper and licenses are attached as `petal-key-source.zip`; no overlay is needed. This repository indexes releases. GitHub automatic source archives contain only this index, not the app source.

Verified on the exact offered APK: **111/111 automated tests on each of Android 10, 15, 16 and 17** using disposable x86_64 emulators and synthetic editors. Android 17 used 16 KB pages. Final runs verified installed APK hashes and restored keyboard settings exactly. No personal phone was used; microphone permission remained denied and no audio was recorded. Fresh host builds, 35 JVM tests per debug/release variant, native/callback regressions, packaged privacy/signature/alignment and theme/resource checks passed. Lint has zero errors and unchanged inherited findings: 223 debug/222 release warnings and one hint each.

See attached `CHECKS.txt` and `SHA256SUMS` for identities, exact checks and limits. Physical ARM64 devices, live TalkBack/Switch Access, actual speech recognition, physical performance/power/thermal measurements and comprehensive low-storage/process-death recovery remain unqualified. ARM32 runtime testing remains excluded.

## Obtainium

- Source: `https://github.com/ClownChowder/petal-key`
- APK filename filter: `^petal-key\.apk$`
- Android package: `app.petalkey.inputmethod.latin`
- Signing certificate SHA-256: `386f097ea7de3749f0b0cc87e433d0f8a8a70cebb1848d7e7cb4bd5f60cff2b4`

The signing identity matches previous previews. This is a debug-signed personal preview, not a production-signed store release. Obtainium detects published releases; it does not build new versions. Signing keys, API keys, pairing tokens, personal data, device settings and raw logs are not published.

## Original authors and credits

See [CREDITS.txt](CREDITS.txt) for original authors, upstream projects and applicable licenses. Original copyright and license notices remain in the source archive and app assets. No upstream endorsement is implied.
