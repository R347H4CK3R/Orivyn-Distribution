# Orivyn Preview for SideStore

## Add the source

In SideStore, open Sources, tap +, and paste:

`https://raw.githubusercontent.com/R347H4CK3R/Orivyn-Distribution/main/source.json`

Orivyn is also listed in the [Strata catalog](https://raw.githubusercontent.com/R347H4CK3R/BOZ-Strata-Source/main/strata-source.json) and the [shared source](https://raw.githubusercontent.com/R347H4CK3R/OmniForge/main/unified-source.json). These feeds identify the same app.

## Current unfinished preview

Orivyn **0.1.1, build 10**, unsigned ARM64 IPA for **iOS 26.0+**. Your installer must sign it for your account and device.

[Download build 10](https://github.com/R347H4CK3R/Orivyn/releases/download/orivyn-v0.1.1-build10/Orivyn-0.1.1-build10-unsigned.ipa)

- Size: 37,141,596 bytes.
- SHA-256: `65ca3580cbba4ea8513a4dcb0bc97e2fe67933ba13aea1ad38f039f75b282bf8`.
- Application identifier: `app.jarvisevo.ios`; preserve existing data and signing identity when updating.
- Package source: `40844c2d96441b8183f231fb27e8a52faa1db80c`.
- [Package verification](https://github.com/R347H4CK3R/Orivyn/actions/runs/43687359101) and [application verification](https://github.com/R347H4CK3R/Orivyn/actions/runs/43685204421).

Includes reviewed native search/read/answer for approved single-message plans, the local LFM vision option, and the history-import presentation fix. Models download separately. The native reviewed route requires the Qwen3 1.7B Q4_K_M model and explicit scope approval. Vision setup displays its model license and limitations before download.

The unchanged application source at `03b9c5cc` passed 1,040 core tests (1,035 passed, five skipped, zero failures), one actual reviewed-model simulator test with three native decisions, and one actual LFM simulator smoke test. The final tooling-only packaging commit passed clean unsigned Release compilation, runtime provenance and IPA/resource/license verification. The full combined UI suite and generic-agent gate were not rerun for this candidate.

General autonomy remains unreliable; broad vision still fails a frozen counting case (9/10 synthetic cases). Automatic live sync is disabled. Physical-device installation, signing refresh, voice, memory/thermal behavior and device runtime remain unverified. A process termination may leave a temporary model snapshot. This is not completed 1.0.0. See the [release notes](https://github.com/R347H4CK3R/Orivyn/releases/tag/orivyn-v0.1.1-build10) for complete scope and evidence.

## Installation

Follow the [official SideStore setup](https://sidestore.io/), add the source, and install Orivyn. Keep Apple credentials and pairing files private. This repository does not sign or install apps automatically. Free signing limits and periodic refresh apply.

Download a model in the app, ask a short question, relaunch and check history/model persistence, then test offline. Report problems with the build number, device and iOS version; never share credentials or pairing files.

Orivyn has no paid app tiers. Optional remote providers may charge. Selected context is sent only when the corresponding remote provider is enabled; model downloads contact listed publisher hosts. Application source is public. Required third-party notices are bundled. No signing keys, model weights or personal conversations are included. Orivyn is independent software, not an OpenAI product.
