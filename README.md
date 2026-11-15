# Orivyn Preview for SideStore

## Add the source

In SideStore, open Sources, tap +, and paste:

`https://raw.githubusercontent.com/R347H4CK3R/Orivyn-Distribution/main/source.json`

Orivyn is also listed in the [Strata catalog](https://raw.githubusercontent.com/R347H4CK3R/BOZ-Strata-Source/main/strata-source.json) and the [shared source](https://raw.githubusercontent.com/R347H4CK3R/OmniForge/main/unified-source.json). These feeds identify the same app.

## Current unfinished preview

Orivyn **0.1.1, build 11**, unsigned ARM64 IPA for **iOS 26.0+**. Your installer must sign it for your account and device.

[Download build 11](https://github.com/R347H4CK3R/Orivyn/releases/download/orivyn-v0.1.1-build11/Orivyn-0.1.1-build11-unsigned.ipa)

- Size: 37,156,968 bytes.
- SHA-256: `499a0a1a2c335fab62b23a0b33be5ef1407278655de5f65bf43d5c22917ab7e9`.
- Application identifier: `app.jarvisevo.ios`; preserve existing data and signing identity when updating.
- Package source: `3f96a41b363e3b663f69497fef4bd698fb1fa514`.
- [Package verification](https://github.com/R347H4CK3R/Orivyn/actions/runs/43723555076) and [host tests / iOS compile](https://github.com/R347H4CK3R/Orivyn/actions/runs/43722288003).

Adds separate confirmation before replacing conversation history. Preserve-local remains the default. Existing native tools, local LFM vision and transcript features remain included; models download separately.

The integrated source passed 152 macOS host tests with zero failures or skips, including synthetic local-file fixtures through production confirmation state, coordinated file reading and SQLite storage. This does not execute AppModel or Files UI. iOS build-for-testing compiled successfully but did not execute iOS tests. The device Release build and independent IPA inspection passed. Actual selected-file confirmation UI, external file-provider grants and physical-device behavior remain unverified.

General autonomy and broad vision remain unreliable; automatic live sync is disabled. Physical-device installation, signing refresh, voice and memory/thermal performance are unverified. A process termination may leave a temporary model snapshot. This is not completed 1.0.0. See the [release notes](https://github.com/R347H4CK3R/Orivyn/releases/tag/orivyn-v0.1.1-build11) for complete scope and evidence.

## Installation

Follow the [official SideStore setup](https://sidestore.io/), add the source, and install Orivyn. Keep Apple credentials and pairing files private. This repository does not sign or install apps automatically. Free signing limits and periodic refresh apply.

Download a model in the app, ask a short question, relaunch and check history/model persistence, then test offline. Report problems with the build number, device and iOS version; never share credentials or pairing files.

Orivyn has no paid app tiers. Optional remote providers may charge. Selected context is sent only when the corresponding remote provider is enabled; model downloads contact listed publisher hosts. Application source is public. Required third-party notices are bundled. No signing keys, model weights or personal conversations are included. Orivyn is independent software, not an OpenAI product.
