# Petal Key

Offline English-US Android keyboard for Android10+. No INTERNET permission,analytics,advertising,cloud inference,runtime downloads or typed-text persistence.

Current personal **Preview:0.1.33-preview (version code34)**. Fixes first-phrase shutdown in tap-to-talk:normal final results/no-match/speech-timeout keep the bounded dictation session open and resume on-device recognition after a pause. Tap the speech bubble again or Stop to insert completed phrases once;Cancel discards them. Space and saved settings stay unchanged.

Completed phrases stay only in memory (10000-character cap). The existing one-minute safety limit requests Stop;final results have a five-second deadline,then only completed phrases are inserted. A missing provider callback can lose the unfinished final phrase. A15-second silence hint is requested but provider-dependent;there may be brief listening gaps during restart. The panel shows Resuming until a real ready callback;waveform follows actual provider levels. Android12+ installed on-device English support required. No audio/transcript files,cloud fallback,downloads or new permissions.

Download `petal-key.apk` from [the verified preview](https://github.com/ClownChowder/petal-key/releases/tag/v0.1.33-preview). Complete corresponding source/tests/build files/licenses:`petal-key-source.zip`. Automatic GitHub archives contain only this release index.

Verified exact APK:**33/33 focused tests each Android10,15,16,17 x86_64 emulator** (132executions),plus37 JVM tests per debug/release variant. New regressions cover pauses/multiple phrases,duplicate/retired callbacks,Stop/Cancel between attempts,protected-field interruption,safety cap/finalization fallback,text bounds and timer/buffer cleanup. Existing checks cover both QWERTY sizes,18themes,automated accessibility,waveform/lifecycle,editing and settings. Exact app/test hashes matched;IME settings restored. Fake speech engines/synthetic text,no microphone grants/audio. Android17 uses16KB pages.

Fresh builds,packaged privacy/exported guards/backup exclusions,signer/alignment,source integrity/secret-pattern scan,runner safety and resource/theme checks passed. Lint:zero errors,222debug/221release inherited warnings and1hint each;no new finding identities. CHECKS.txt and SHA256SUMS bind final assets and distinguish initial attempts from final results. Regression first failed on0.1.32,which immediately inserted the first phrase and ended dictation.

**Limits:**physical-phone pause/restart timing/real speech,live TalkBack/Switch Access,full typing suite,native sanitizer/callback suites,physical performance/power/thermal and comprehensive recovery not rerun/qualified for this update. Existing narrow-QWERTY target limits remain. No phone access/install/settings changes. ARM32 runtime excluded.

Verified previews are GitHub Latest for Obtainium discovery while retaining preview names and honest limits. Latest is distribution metadata,not production qualification.

## Obtainium

- Source: `https://github.com/ClownChowder/petal-key`
- APK filename filter: `^petal-key\.apk$`
- Android package: `app.petalkey.inputmethod.latin`
- Signing certificate SHA-256: `386f097ea7de3749f0b0cc87e433d0f8a8a70cebb1848d7e7cb4bd5f60cff2b4`

The signing identity matches previous previews. This is a debug-signed personal preview, not a production-signed store release. Obtainium detects published releases; it does not build new versions. Signing keys, API keys, pairing tokens, personal data, device settings and raw logs are not published.

## Original authors and credits

See [CREDITS.txt](CREDITS.txt) for original authors, upstream projects and applicable licenses. Original copyright and license notices remain in the source archive and app assets. No upstream endorsement is implied.
