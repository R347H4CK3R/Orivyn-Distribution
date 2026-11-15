# Orivyn Preview for SideStore

## Add the source

In SideStore, open Sources, tap +, and paste:

`https://raw.githubusercontent.com/R347H4CK3R/Orivyn-Distribution/main/source.json`

Orivyn is also listed in the [Strata catalog](https://raw.githubusercontent.com/R347H4CK3R/BOZ-Strata-Source/main/strata-source.json) and the [shared source](https://raw.githubusercontent.com/R347H4CK3R/OmniForge/main/unified-source.json). These feeds identify the same app.

## Current unfinished preview

Orivyn **0.1.1, build 12**, unsigned ARM64 IPA for **iOS 26.0+**. Your installer must sign it for your account and device.

[Download build 12](https://github.com/R347H4CK3R/Orivyn/releases/download/orivyn-v0.1.1-build12/Orivyn-0.1.1-build12-unsigned.ipa)

- Size: 37,168,551 bytes.
- SHA-256: `9e873964337b24b03c5018158d1518f20b7d6eda892324f20aaad7c3b4f62352`.
- Application identifier: `app.jarvisevo.ios`; preserve existing data and signing identity when updating.
- Package source: `3cc225959b9f78865a21aef18adfb7a603ab6932`.
- [Host snapshot checks and package verification](https://github.com/R347H4CK3R/Orivyn/actions/runs/43729015018).

Adds conservative cleanup of recognized orphan model snapshots on the next native model load that creates a new snapshot. Live leases, installed downloads, unmarked directories and unexpected files are preserved. Separate confirmation before replacing conversation history is retained. Preserve-local remains the default. Existing native tools, local LFM vision and transcript features remain included; models download separately.

The exact build12 source passed 10 Darwin filesystem tests with no failures or skips, plus a synthetic process-lifetime test verifying live-lease preservation and orphan recovery after terminating only the test subprocess. The combined native runtime, Release device build and independent IPA inspection passed. These checks do not execute actual iPhone inference or verify memory-mapped model lifetime. The earlier backup change's host evidence remains separate; selected-file confirmation UI, external file-provider grants and physical-device behavior remain unverified.

General autonomy and broad vision remain unreliable; automatic live sync is disabled. Physical-device installation, signing refresh, voice and memory/thermal performance are unverified. Unmarked legacy orphan snapshots remain untouched for safety. This is not completed 1.0.0. See the [release notes](https://github.com/R347H4CK3R/Orivyn/releases/tag/orivyn-v0.1.1-build12) for complete scope and evidence.

## Installation

Follow the [official SideStore setup](https://sidestore.io/), add the source, and install Orivyn. Keep Apple credentials and pairing files private. This repository does not sign or install apps automatically. Free signing limits and periodic refresh apply.

Download a model in the app, ask a short question, relaunch and check history/model persistence, then test offline. Report problems with the build number, device and iOS version; never share credentials or pairing files.

Orivyn has no paid app tiers. Optional remote providers may charge. Selected context is sent only when the corresponding remote provider is enabled; model downloads contact listed publisher hosts. Application source is public. Required third-party notices are bundled. No signing keys, model weights or personal conversations are included. Orivyn is independent software, not an OpenAI product.
