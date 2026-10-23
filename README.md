# Petal Key

Offline English-US Android keyboard for Android10 and newer. Works inside existing messaging and other apps. Optional voice typing uses Android's on-device recognizer only. No Internet permission, analytics, advertising, cloud inference or automatic typed-text persistence.

Download the APK and full corresponding source ZIP from [Releases](https://github.com/ClownChowder/petal-key/releases). This repository indexes personal previews; GitHub's automatic source archives are not the app source. Use the explicitly attached `petal-key-source.zip`. Original copyright notices and licenses remain in the source and app assets.

Current preview: **0.1.25-preview (version code26)**. Fixes native coordinate bounds, cancellation, stale tools previews, ended-session text/suggestion references and late batch callbacks after canceled/replaced gestures.

**Automated Android runtime checks passed on the exact published APK:** Android 10 and 17 each passed 109 tests; Android 15 and 16 each passed 22 focused tests. Android 17 used 16 KB pages. Disposable x86_64 emulators used synthetic editors; final keyboard settings were restored exactly. No personal phone was used or microphone granted. Initial test-readiness and factory-settings failures, test/tool repairs, APK/test identities and limits are documented in `RUNTIME-CHECKS.txt`. Apply `RUNTIME-TEST-SOURCE.zip` over the original source ZIP for those test/tool-only updates; application production inputs and APK are unchanged. `RUNTIME-SHA256SUMS` covers the public assets.

Fresh host checks passed 35 JVM tests per debug/release variant, 10 callback cases, 10 native sanitizer cases, builds, packaged privacy/signature/native alignment and theme/resource checks. Lint has zero errors; 223 debug/222 release inherited warnings and one hint each remain. `CHECKS.txt` preserves the initial host assessment. Physical ARM64 devices, live TalkBack/Switch Access, speech recognition, physical performance/power/thermal measurements and comprehensive low-storage/process-death recovery remain unqualified. ARM32 runtime testing stays excluded.

## Obtainium

- Source:`https://github.com/ClownChowder/petal-key`
- APK filename filter:`^petal-key\.apk$`
- Android package:`app.petalkey.inputmethod.latin`
- Signing certificate SHA-256:`386f097ea7de3749f0b0cc87e433d0f8a8a70cebb1848d7e7cb4bd5f60cff2b4`

The signing identity matches previous published previews. These are debug-signed personal previews, not production-signed store releases. Obtainium detects published releases; it does not develop or build new versions. Signing keys, saved API keys, pairing tokens, personal app data and raw test logs are not published. Checksums are attached.

## Original authors and credits

See [CREDITS.txt](CREDITS.txt) for original authors, upstream projects, recording/model creators and applicable licenses. Original license and copyright notices remain in corresponding source archives and app assets. No upstream endorsement is implied.
