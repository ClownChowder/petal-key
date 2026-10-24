# Petal Key

Offline English-US Android keyboard for Android 10+. No INTERNET permission, analytics, advertising, cloud inference, runtime downloads or automatic typed-text persistence.

Current personal **Preview: 0.1.31-preview (version code 32)**. Adds Standard Light and Standard Dark (18 themes total), matching neutral launcher icons and the approved speech bubble with three rounded sound bars for voice typing across all themes. Existing16 palette values,40 legacy selections/launcher vectors, keycap shapes and preferences are preserved. New saved IDs40/41 are appended; no settings reset. Offline waveform and hold-to-talk behavior remain unchanged.

Download `petal-key.apk` from [the verified preview](https://github.com/ClownChowder/petal-key/releases/tag/v0.1.31-preview). Complete corresponding source/tests/Gradle wrapper/licenses: `petal-key-source.zip`. This repository indexes releases; GitHub automatic source archives contain only this index.

Verified exact APK: **29/29 focused tests on each Android 10, 15, 16 and 17 x86_64 emulator** (116 executions). Fake recognizers and synthetic editors only; no microphone grants/audio. Renders all18 themes, checks actual keycap/edge/background and matching launcher colors, voice icon silhouette/tint/label in both QWERTY sizes, every theme/alias selection and migration, plus relative level boundaries, release/end/cancel/stale callbacks, 24 repeated sessions per emulator across regular/large QWERTY, accessibility/panel bounds, protected fields, lifecycle cancellation, screen-touch hold/release and settings. Installed app/test hashes matched and keyboard settings were restored. Android 17 uses 16 KB pages.

Fresh debug/release builds, 37 JVM tests per variant, packaged privacy/signature/alignment, runner safety and theme/resource checks passed. Lint: zero errors, 222 debug/221 release inherited warnings and one hint each; no new issue identities. `CHECKS.txt` and `SHA256SUMS` contain exact identities, initial attempts (including an icon antialias comparison refinement), final results and limits.

Provider RMS callbacks are not guaranteed by Android; status messages still work when levels are unavailable. Relative waveform is not a calibrated sound meter. Physical-phone waveform/real-provider behavior, the full 123-test typing suite, live TalkBack/Switch Access, native sanitizer/callback suites and physical performance/power/thermal were not qualified in this update. No personal-phone installation or settings changes. ARM32 runtime testing remains excluded.

Verified previews are marked GitHub Latest for Obtainium's default filters while retaining preview names and honest limits. Latest is distribution metadata, not production qualification.

## Obtainium

- Source: `https://github.com/ClownChowder/petal-key`
- APK filename filter: `^petal-key\.apk$`
- Android package: `app.petalkey.inputmethod.latin`
- Signing certificate SHA-256: `386f097ea7de3749f0b0cc87e433d0f8a8a70cebb1848d7e7cb4bd5f60cff2b4`

The signing identity matches previous previews. This is a debug-signed personal preview, not a production-signed store release. Obtainium detects published releases; it does not build new versions. Signing keys, API keys, pairing tokens, personal data, device settings and raw logs are not published.

## Original authors and credits

See [CREDITS.txt](CREDITS.txt) for original authors, upstream projects and applicable licenses. Original copyright and license notices remain in the source archive and app assets. No upstream endorsement is implied.
