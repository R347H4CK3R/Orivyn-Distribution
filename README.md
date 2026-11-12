# Orivyn Preview for SideStore

Free binary distribution only. The Orivyn application source repository remains private. This repository is separate from Jarvis Preview and does not change it.

## Add the source

In SideStore, open Sources, tap +, and paste:

`https://raw.githubusercontent.com/R347H4CK3R/Orivyn-Distribution/main/source.json`

Or open [Add Orivyn Preview to SideStore](sidestore://source?url=https://raw.githubusercontent.com/R347H4CK3R/Orivyn-Distribution/main/source.json) on a device with SideStore installed. This repository does not sign or install apps automatically.

## Current development preview

- Orivyn **0.1.0, build 4**, for **iOS 26.0+**, ARM64 iPhone.
- Download: [Orivyn-0.1.0-build4-distribution-unsigned.ipa](https://raw.githubusercontent.com/R347H4CK3R/Orivyn-Distribution/main/Orivyn-0.1.0-build4-distribution-unsigned.ipa)
- Package size: **4,192,466 bytes**.
- SHA-256: `196091d0989f39a01787491efcfb7d1461bbca3a2f9d26f4d82b5bc7fa12ee7d`.
- Application identifier: `app.jarvisevo.ios`, preserved for existing Orivyn/Jarvis-EVO data. This is not the separate Jarvis/GhostAI app.

The original candidate passed 62 package/source checks, 288 native tests and 27 UI tests on an iPhone 16 Plus simulator, including the actual default-model download, local answer and relaunch persistence. This distribution copy adds only the bundled llama.cpp MIT license. Every existing payload entry, including executable, framework, assets and Info.plist, is byte-identical to the tested candidate. Both llama.cpp and KaTeX notices are included in the IPA. No model weights, source code, test fixtures, credentials or personal conversations are included.

**Not a fully device-accepted release.** Physical SideStore installation/refresh, microphone and speech behavior, offline use, large-model memory/thermal performance, and LiveContainer compatibility have not been verified. Local reminders, cross-app incoming-text staging and external account integrations are not in this preview. No background AI execution is promised.

## Install and check

1. Follow the current [official SideStore setup](https://sidestore.io/). Keep your Apple credentials and pairing files private.
2. Add the source above, or download the IPA and import it into SideStore. SideStore must sign this unsigned app for your account/device. Free signing limits and periodic refresh still apply.
3. Open Orivyn, then Models. Start with the default approximately 491 MB Qwen2.5 0.5B model on Wi-Fi. Larger catalog options require more memory and storage; weights are not bundled.
4. Ask a short question, relaunch, and confirm the conversation/model persist. Then test offline with connectivity disabled.
5. Test voice and SideStore refresh separately. Report the exact error, device and iOS version, but never credentials or pairing files.

Orivyn has no subscriptions, pay tiers or in-app unlocks. Optional external endpoints are disabled by default and their providers may charge separately. Local history stays on device; explicitly enabling a remote endpoint sends selected context to that endpoint. Model downloads contact the listed publisher hosts.

Orivyn is independent software, not an OpenAI product. The icon is original Orivyn artwork. Third-party license notices apply to their respective components. No Apple account, signing profile or additional entitlement is distributed here.
