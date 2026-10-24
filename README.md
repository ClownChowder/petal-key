# Petal Key

Offline English-US Android keyboard for Android 10+. No INTERNET permission, analytics, advertising, cloud inference, runtime downloads or automatic typed-text persistence.

Current personal **Preview: 0.1.29-preview (version code 30)**. Completed setup buttons are disabled with readable grey styling: Keyboard enabled / Keyboard active, and Microphone allowed only when actual microphone permission is granted. Keyboard status refreshes while settings remain visible; permission is rechecked on return. The keyboard microphone remains usable. No settings reset or automatic microphone grant/recording.

Download `petal-key.apk` from [the verified preview](https://github.com/ClownChowder/petal-key/releases/tag/v0.1.29-preview). Complete corresponding source/tests/Gradle wrapper/licenses: `petal-key-source.zip`. This repository indexes releases; GitHub automatic source archives contain only this index.

Verified exact APK: **15/15 focused tests on each Android 10, 15, 16 and 17 emulator**, plus **five live visible setup-state transitions on each**. Synthetic editors/disposable x86_64 emulators; Android 17 uses 16 KB pages. Final app/test hashes matched and keyboard settings were restored. Granted-permission styling is simulated only in the UI binding; tests verify no actual permission/preference change. No microphone grants or audio recording.

Fresh debug/release builds, 37 JVM tests per variant, packaged privacy/signature/alignment, runner safety and theme/resource checks passed. Lint: zero errors, 222 debug/221 release warnings and one hint each; one inherited warning removed, no new findings. `CHECKS.txt` and `SHA256SUMS` contain exact identities, initial failed attempts, final results and limits.

The full 122-test typing suite, live TalkBack/Switch Access and native sanitizer/callback suites were not rerun for this setup-only change. Physical-phone runtime, real speech/model readiness/accuracy, physical performance/power/thermal and comprehensive recovery remain unqualified. No personal phone installation. ARM32 runtime testing remains excluded.

Verified previews are marked GitHub Latest for Obtainium's default filters while retaining preview names and honest limits. Latest is distribution metadata, not production qualification.

## Obtainium

- Source: `https://github.com/ClownChowder/petal-key`
- APK filename filter: `^petal-key\.apk$`
- Android package: `app.petalkey.inputmethod.latin`
- Signing certificate SHA-256: `386f097ea7de3749f0b0cc87e433d0f8a8a70cebb1848d7e7cb4bd5f60cff2b4`

The signing identity matches previous previews. This is a debug-signed personal preview, not a production-signed store release. Obtainium detects published releases; it does not build new versions. Signing keys, API keys, pairing tokens, personal data, device settings and raw logs are not published.

## Original authors and credits

See [CREDITS.txt](CREDITS.txt) for original authors, upstream projects and applicable licenses. Original copyright and license notices remain in the source archive and app assets. No upstream endorsement is implied.
