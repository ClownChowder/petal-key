# Petal Key

Offline English-US Android keyboard for Android 10 and newer. Works inside existing messaging and other apps. Optional voice typing uses Android's on-device recognizer only. No INTERNET permission, analytics, advertising, cloud inference or automatic typed-text persistence.

Current personal preview: **0.1.27-preview (version code 28)**. Adds an optional number row (off by default), editing panel, and adjustable popup-letter size and linger. The larger microphone supports hold-to-talk and release-to-stop, with explicit start/stop accessibility activation and visible unavailable/error notices. Existing settings are preserved. Protected fields continue to suppress previews, editing tools and voice typing.

Download `petal-key.apk` from [the verified preview](https://github.com/ClownChowder/petal-key/releases/tag/v0.1.27-preview). Complete corresponding source, tests, Gradle wrapper and licenses are attached as `petal-key-source.zip`; no overlay is needed. This repository indexes releases. GitHub automatic source archives contain only this index, not the app source.

Verified on the exact offered APK: **119/119 automated tests on each of Android 10, 15, 16 and 17** using disposable x86_64 emulators and synthetic editors. Android 17 used 16 KB pages. Actual TalkBack and Switch Access services each completed 39 workflow phases on the Android 17 emulator, using touch exploration/double taps and hardware-style Next/Select input. Final runs verified installed APK/test hashes and restored keyboard/accessibility settings. Fresh debug/release builds, 37 JVM tests per variant, native/callback regressions, packaged privacy/signature/alignment and theme/resource checks passed. Lint has zero errors and unchanged inherited findings: 223 debug/222 release warnings and one hint each.

**Actual speech is not qualified.** Automated tests use fake recognizers, never grant microphone permission or record audio. Offline dictation requires Android 12+ and installed on-device English support; no cloud fallback or model download is added. Release requests stop; final recognition can arrive later. This APK was not installed on a personal phone. Physical ARM64 runtime/user accessibility, real speech/model readiness/accuracy, physical performance/power/thermal measurements and comprehensive low-storage/process-death recovery remain unqualified. ARM32 runtime testing remains excluded.

See attached `CHECKS.txt` and `SHA256SUMS` for exact identities, reproduced fixes, failed initial attempts, final checks and limits. Failed evidence is retained locally; no raw logs are uploaded.

## Obtainium

- Source: `https://github.com/ClownChowder/petal-key`
- APK filename filter: `^petal-key\.apk$`
- Android package: `app.petalkey.inputmethod.latin`
- Signing certificate SHA-256: `386f097ea7de3749f0b0cc87e433d0f8a8a70cebb1848d7e7cb4bd5f60cff2b4`

The signing identity matches previous previews. This is a debug-signed personal preview, not a production-signed store release. Obtainium detects published releases; it does not build new versions. Signing keys, API keys, pairing tokens, personal data, device settings and raw logs are not published.

## Original authors and credits

See [CREDITS.txt](CREDITS.txt) for original authors, upstream projects and applicable licenses. Original copyright and license notices remain in the source archive and app assets. No upstream endorsement is implied.
