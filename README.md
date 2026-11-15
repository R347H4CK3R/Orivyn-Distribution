# Orivyn Preview for SideStore

## Add the source

In SideStore, open Sources, tap +, and paste:

`https://raw.githubusercontent.com/R347H4CK3R/Orivyn-Distribution/main/source.json`

Orivyn is also listed in the [Strata catalog](https://raw.githubusercontent.com/R347H4CK3R/BOZ-Strata-Source/main/strata-source.json) and the [shared source](https://raw.githubusercontent.com/R347H4CK3R/OmniForge/main/unified-source.json). These feeds identify the same app.

## Current unfinished preview

Orivyn **0.1.1, build 9**, unsigned ARM64 IPA for **iOS 26.0+**. SideStore signs it for your account and device.

[Download build 9](https://github.com/R347H4CK3R/Orivyn/releases/download/orivyn-v0.1.1-build9/Orivyn-0.1.1-build9-unsigned.ipa)

- Size: 41,853,828 bytes.
- SHA-256: `0b4baf9761ea721959c97f0948b0e0aacd1f64f469d543fae36fe2c745d1fc45`.
- Application identifier: `app.jarvisevo.ios`; preserve existing data and signing identity when updating.
- Source: `32ddf39174ce7afe0b026f26380b5b0d6ad66a04`.
- Build: https://github.com/R347H4CK3R/Orivyn/actions/runs/43679464506.

Includes local chat, downloadable models, reviewed read workflows, native tools and local image analysis. Models download separately. General autonomy and broad vision remain unreliable; automatic cross-device sync is unfinished and disabled. Known UI bugs include New conversation sometimes retaining the previous response. Later development changes are not included in this package.

Unsigned device compilation, runtime archive validation, IPA structure/resource checks and independent identity/hash inspection passed. For this exact source, 1,032 native core tests executed with 5 skipped and zero failures. UI-0 passed; UI-2 and the required general-agent search/read case failed. These failures are retained and disclosed. Physical-device installation, signing refresh, voice, memory/thermal behavior and runtime remain unverified. This is not completed 1.0.0.

## Installation

Follow the [official SideStore setup](https://sidestore.io/), add the source, and install Orivyn. Keep Apple credentials and pairing files private. This repository does not sign or install apps automatically. Free signing limits and periodic refresh apply.

Download a model in the app, ask a short question, relaunch and check history/model persistence, then test offline. Report problems with the build number, device and iOS version; never share credentials or pairing files.

Orivyn has no paid app tiers. Optional remote providers may charge. Selected context is sent only when the corresponding remote provider is enabled; model downloads contact listed publisher hosts. Application source is public. Required third-party notices are bundled. No signing keys, model weights or personal conversations are included. Orivyn is independent software, not an OpenAI product.
