# Orivyn Preview for SideStore

## Add the source

In SideStore, open Sources, tap +, and paste:

`https://raw.githubusercontent.com/R347H4CK3R/Orivyn-Distribution/main/source.json`

Orivyn is also listed in the [Strata catalog](https://raw.githubusercontent.com/R347H4CK3R/BOZ-Strata-Source/main/strata-source.json) and the [shared source](https://raw.githubusercontent.com/R347H4CK3R/OmniForge/main/unified-source.json). These feeds identify the same app.

## Current unfinished preview

Orivyn **0.1.1, build 8**, unsigned ARM64 IPA for **iOS 26.0+**. SideStore signs it for your account and device.

[Download build 8](https://github.com/R347H4CK3R/Orivyn/releases/download/orivyn-v0.1.1-build8/Orivyn-0.1.1-build8-unsigned.ipa)

- Size: 37,072,679 bytes.
- SHA-256: `04c2bd77eb6f807eb17c24bce6ff0a8cf88cae5d74e0e43955cba9230d01723d`.
- Application identifier: `app.jarvisevo.ios`; preserve existing data and signing identity when updating.
- Source: `a6c696a89a2e5a6224e220b6772b62614d30b4df`.
- Build: https://github.com/R347H4CK3R/Orivyn/actions/runs/43660234783.

Includes local chat, downloadable models, reviewed read workflows, native tools and local image analysis. Models download separately. General autonomy and broad vision remain unreliable; automatic cross-device sync is unfinished and disabled. Known UI bugs include New conversation sometimes retaining the previous response. Later development changes are not included in this package.

Unsigned device compilation, runtime archive validation, IPA structure/resource checks and independent identity/hash inspection passed. Native unit/UI tests were not run for this exact package. Physical-device installation, signing refresh, voice, memory/thermal behavior and runtime remain unverified. This is not completed 1.0.0.

## Installation

Follow the [official SideStore setup](https://sidestore.io/), add the source, and install Orivyn. Keep Apple credentials and pairing files private. This repository does not sign or install apps automatically. Free signing limits and periodic refresh apply.

Download a model in the app, ask a short question, relaunch and check history/model persistence, then test offline. Report problems with the build number, device and iOS version; never share credentials or pairing files.

Orivyn has no paid app tiers. Optional remote providers may charge. Selected context is sent only when the corresponding remote provider is enabled; model downloads contact listed publisher hosts. Application source is public. Required third-party notices are bundled. No signing keys, model weights or personal conversations are included. Orivyn is independent software, not an OpenAI product.
