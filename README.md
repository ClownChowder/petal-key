# Petal Key

Offline English-US Android keyboard for Android 10+. No INTERNET permission, analytics, advertising, cloud inference, runtime downloads or typed-text persistence.

Current personal **Preview: 0.1.32-preview (version code 33)**. Tap the speech bubble once to start voice typing, then tap again to stop. Space stays unchanged. The waveform/status panel remains inside the keyboard window, with Stop and Cancel controls. Both QWERTY sizes and all18 themes share the same action. Saved settings are preserved.

Download `petal-key.apk` from [the verified preview](https://github.com/ClownChowder/petal-key/releases/tag/v0.1.32-preview). Complete corresponding source/tests/build files/licenses: `petal-key-source.zip`. This repository indexes releases; GitHub automatic archives contain only this index.

Verified exact APK: **30/30 focused tests on each Android10,15,16,17 x86_64 emulator** (120 executions), plus37 JVM tests per debug/release variant. Includes real injected two-tap touches in both sizes using fake engines,18 themes,automated accessibility,protected fields,cancellation/late callbacks,waveform lifecycle,panel bounds and settings preservation. App/test hashes matched; keyboard settings restored. No microphone grants or audio recording. Android17 uses16KB pages.

Fresh host builds, packaged privacy/signature/alignment, source integrity/secret-pattern scan, runner safety and theme/resource checks passed. Lint:zero errors,222 debug/221 release inherited warnings plus one hint each; no new finding identities. `CHECKS.txt` and `SHA256SUMS` bind exact assets, initial attempts, final results and limits.

**Limits:**physical-phone two-tap speech and real-provider behavior,live TalkBack/Switch Access,full123-test typing suite,native sanitizer/callback suites,physical performance/battery/thermal and comprehensive recovery were not rerun for this update. Existing narrow-QWERTY target limits remain. No phone installation/settings changes. ARM32 runtime stays excluded. On-device English recognition requires Android12+ and installed offline support; no cloud fallback/model downloads. RMS callbacks are provider-dependent; the waveform is a relative indicator.

Verified previews are marked GitHub Latest for Obtainium default filters while retaining preview names and honest limits. Latest is distribution metadata, not production qualification.

## Obtainium

- Source: `https://github.com/ClownChowder/petal-key`
- APK filename filter: `^petal-key\.apk$`
- Android package: `app.petalkey.inputmethod.latin`
- Signing certificate SHA-256: `386f097ea7de3749f0b0cc87e433d0f8a8a70cebb1848d7e7cb4bd5f60cff2b4`

The signing identity matches previous previews. This is a debug-signed personal preview, not a production-signed store release. Obtainium detects published releases; it does not build new versions. Signing keys, API keys, pairing tokens, personal data, device settings and raw logs are not published.

## Original authors and credits

See [CREDITS.txt](CREDITS.txt) for original authors, upstream projects and applicable licenses. Original copyright and license notices remain in the source archive and app assets. No upstream endorsement is implied.
