# Petal Key

Offline English-US Android keyboard for Android10 and newer. Works inside existing messaging and other apps. Optional voice typing uses Android's on-device recognizer only. No Internet permission, analytics, advertising, cloud inference or automatic typed-text persistence.

Download the APK and full corresponding source ZIP from [Releases](https://github.com/ClownChowder/petal-key/releases). This repository indexes personal previews; GitHub's automatic source archives are not the app source. Use the explicitly attached `petal-key-source.zip`. Original copyright notices and licenses remain in the source and app assets.

Current preview: **0.1.25-preview (version code26)**. Fixes native coordinate bounds, cancellation, stale tools previews, ended-session text/suggestion references and late batch callbacks after canceled/replaced gestures.

**Host-verified only for this APK; no Android installation or runtime testing was authorized.** Fresh checks passed35 JVM tests per debug/release variant,10 callback cases,10 native sanitizer cases, builds, packaged privacy/signature/native alignment and theme/resource checks. Lint has zero errors;223 debug/222 release warnings and1hint each remain. See attached `CHECKS.txt` for exact verification, source/artifact identities and limits. Android lifecycle/correction/undo, live speech/accessibility, device compatibility, physical performance/memory and battery/thermal checks remain unqualified. ARM32 runtime testing stays excluded.

## Obtainium

- Source:`https://github.com/ClownChowder/petal-key`
- APK filename filter:`^petal-key\.apk$`
- Android package:`app.petalkey.inputmethod.latin`
- Signing certificate SHA-256:`386f097ea7de3749f0b0cc87e433d0f8a8a70cebb1848d7e7cb4bd5f60cff2b4`

The signing identity matches previous published previews. These are debug-signed personal previews, not production-signed store releases. Obtainium detects published releases; it does not develop or build new versions. Signing keys, saved API keys, pairing tokens, personal app data and raw test logs are not published. Checksums are attached.

## Original authors and credits

See [CREDITS.txt](CREDITS.txt) for original authors, upstream projects, recording/model creators and applicable licenses. Original license and copyright notices remain in corresponding source archives and app assets. No upstream endorsement is implied.
