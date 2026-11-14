# Orivyn Preview for SideStore

Free binary distribution only. The Orivyn application source repository remains private. This repository is separate from Jarvis Preview and does not change it.

## Add the source

Orivyn is also available in the shared Strata catalog with the other apps:

`https://raw.githubusercontent.com/R347H4CK3R/OmniForge/main/unified-source.json`

The separate Orivyn-only source remains available below. Add either source; they identify the same app.

In SideStore, open Sources, tap +, and paste:

`https://raw.githubusercontent.com/R347H4CK3R/Orivyn-Distribution/main/source.json`

Or open [Add Orivyn Preview to SideStore](sidestore://source?url=https://raw.githubusercontent.com/R347H4CK3R/Orivyn-Distribution/main/source.json) on a device with SideStore installed. This repository does not sign or install apps automatically.

## Current development preview

- Orivyn **0.1.1, build 6**, for **iOS 26.0+**, ARM64 iPhone.
- [Download the development preview](https://github.com/R347H4CK3R/Orivyn-Distribution/releases/download/orivyn-v0.1.1-build6/Orivyn-0.1.1-build6-unsigned.ipa)
- Package size: **35,042,297 bytes**.
- SHA-256: `86adf180469d44b927cfc078adb5fcf315c5a4da9a1078f613788771640db79e`.
- Application identifier: `app.jarvisevo.ios`, preserved for existing Orivyn data.

Independent local-first iPhone assistant with downloadable models, chat history, documents and image text recognition, voice, projects and response preferences. Build 6 adds stricter remote-stream validation and reviewed source-patch export. No subscriptions or paid app tiers; optional remote providers may charge. Unsigned iOS26 development preview; SideStore must sign it. Models download separately. Portable checks, native device compilation and IPA inspection passed. Exact-build native unit/UI tests and physical-device installation/refresh, voice, memory/thermal behavior and Files export remain unverified. General autonomous tool orchestration, broad vision and automatic cross-device sync remain unfinished. Not completed 1.0.0 or an OpenAI product.

400 Foundation Swift, 104 JavaScript agent, 39 VM component and 158 Python tests passed; one existing tokenizer test was skipped. Native device Release compilation and IPA inspection passed for source `319d6aed0a4e7543d23f96bb2de882cf68616348`. Native unit/UI tests were not run for this exact build. Physical-device acceptance remains pending. Required llama.cpp and KaTeX notices are bundled. No private source archive, signing keys, model weights or personal conversations are included.

## Install and check

1. Follow the current [official SideStore setup](https://sidestore.io/). Keep your Apple credentials and pairing files private.
2. Add the source above, or download the IPA and import it into SideStore. SideStore must sign this unsigned app for your account/device. Free signing limits and periodic refresh still apply.
3. Open Orivyn, then Models. Start with the default approximately 491 MB Qwen2.5 0.5B model on Wi-Fi. Larger catalog options require more memory and storage; weights are not bundled.
4. Ask a short question, relaunch, and confirm the conversation/model persist. Then test offline with connectivity disabled.
5. Test voice and SideStore refresh separately. Report the exact error, device and iOS version, but never credentials or pairing files.

Orivyn has no subscriptions, pay tiers or in-app unlocks. Optional external endpoints are disabled by default and their providers may charge separately. Local history stays on device; explicitly enabling a remote endpoint sends selected context to that endpoint. Model downloads contact the listed publisher hosts.

Orivyn is independent software, not an OpenAI product. The icon is original Orivyn artwork. Third-party license notices apply to their respective components. No Apple account, signing profile or additional entitlement is distributed here.
