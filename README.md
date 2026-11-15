# Orivyn Preview for SideStore

## Add the source

In SideStore, open Sources, tap +, and paste:

`https://raw.githubusercontent.com/R347H4CK3R/Orivyn-Distribution/main/source.json`

Orivyn is also listed in the [Strata catalog](https://raw.githubusercontent.com/R347H4CK3R/BOZ-Strata-Source/main/strata-source.json) and the [shared source](https://raw.githubusercontent.com/R347H4CK3R/OmniForge/main/unified-source.json). These feeds identify the same app.

## Current unfinished preview

Orivyn **0.1.1, build 13**, unsigned ARM64 IPA for **iOS 26.0+**. Your installer must sign it for your account and device.

[Download build 13](https://github.com/R347H4CK3R/Orivyn/releases/download/orivyn-v0.1.1-build13/Orivyn-0.1.1-build13-unsigned.ipa)

- Size: 37,169,284 bytes.
- SHA-256: `90952536433c54f5b2850aeed9da3c01d5738fbf32a9798056f93647152f9cbb`.
- Application identifier: `app.jarvisevo.ios`; preserve existing data and signing identity when updating.
- Package source: `10bb4038d23389fb215c08c34428abe0a3ecb027`.
- [Host snapshot checks and package verification](https://github.com/R347H4CK3R/Orivyn/actions/runs/43732749341).

Preserves unexpected model-recovery staging data rather than recursively deleting it. Unknown entries block recovery for inspection before live files change; normal rollback remains supported. Prior model-snapshot leases/cleanup and explicit backup replacement confirmation are retained. Preserve-local remains the default; models download separately.

The exact build13 source passed 19 Darwin filesystem recovery tests with no failures or skips. The combined native runtime, Release device build and independent IPA inspection passed. These checks do not verify actual iPhone inference, memory-mapped model lifetime, selected-file confirmation UI, external file-provider grants, hostile concurrent writers or power-loss durability. Unexpected temporary staging names can require inspection rather than automatic recovery.

General autonomy and broad vision remain unreliable; automatic live sync is disabled. Physical-device installation, signing refresh, voice and memory/thermal performance are unverified. Unmarked legacy orphan snapshots remain untouched for safety. This is not completed 1.0.0. See the [release notes](https://github.com/R347H4CK3R/Orivyn/releases/tag/orivyn-v0.1.1-build13) for complete scope and evidence.

## Installation

Follow the [official SideStore setup](https://sidestore.io/), add the source, and install Orivyn. Keep Apple credentials and pairing files private. This repository does not sign or install apps automatically. Free signing limits and periodic refresh apply.

Download a model in the app, ask a short question, relaunch and check history/model persistence, then test offline. Report problems with the build number, device and iOS version; never share credentials or pairing files.

Orivyn has no paid app tiers. Optional remote providers may charge. Selected context is sent only when the corresponding remote provider is enabled; model downloads contact listed publisher hosts. Application source is public. Required third-party notices are bundled. No signing keys, model weights or personal conversations are included. Orivyn is independent software, not an OpenAI product.
