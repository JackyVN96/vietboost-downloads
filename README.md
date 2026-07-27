# VietBoost Extension Downloads

This repository contains the official packaged downloads for the VietBoost Chrome extension. The VietBoost website and source repository remain private.

## Version 1.1.16

Download [`vietboost-extension-1.1.16-chrome.zip`](./vietboost-extension-1.1.16-chrome.zip), then:

1. Extract the ZIP to a permanent folder on your computer.
2. Open `chrome://extensions` in Google Chrome.
3. Enable **Developer mode**.
4. Select **Load unpacked** and choose the extracted folder.

SHA-256: `AD756F9D419815E1FA30B872D7151434BEE0838B7DD3FFAB4EB4549C80C5C5BE`

### What changed in 1.1.16

- Adds Google Gemini alongside OpenAI and DeepSeek for VietBoost system AI and lets VIP members select the server-configured model.
- Adds encrypted admin configuration for model, per-user rate/day limits, and input/output token pricing; the admin dashboard shows request, token, USD, VND, and recent-user usage data.
- Enforces an atomic database-backed daily system-AI allowance in addition to signed extension sessions, VIP entitlements, user/IP/provider rate limits, strict request validation, and server-only API keys.
- Adds a regression test for the public Douyin share-page resolver, which asks for the public `ratio=default` video stream rather than a preview URL.

## Version 1.1.15

Download [`vietboost-extension-1.1.15-chrome.zip`](./vietboost-extension-1.1.15-chrome.zip), then:

1. Extract the ZIP to a permanent folder on your computer.
2. Open `chrome://extensions` in Google Chrome.
3. Enable **Developer mode**.
4. Select **Load unpacked** and choose the extracted folder.

SHA-256: `8D1E1992570D38E48114DB4431B9AF1F13B3E55A15FE5992758F7A550B5945B3`

### What changed in 1.1.15

- Restores a visible extension settings entry and lets VIP members choose VietBoost system AI or a browser-local personal API key.
- Adds server-admin AI provider settings with encrypted API keys; extension clients receive model metadata only.
- Adds Reddit recognition and media scanning support.
- Reworks Douyin video discovery around its public share metadata and removes avatars/small UI images from post scans.

## Version 1.1.14

Download [`vietboost-extension-1.1.14-chrome.zip`](./vietboost-extension-1.1.14-chrome.zip), then:

1. Extract the ZIP to a permanent folder on your computer.
2. Open `chrome://extensions` in Google Chrome.
3. Enable **Developer mode**.
4. Select **Load unpacked** and choose the extracted folder.

Check the [VietBoost changelog](https://vietboost.net/vi/changelog) before updating. Only use downloads published in this repository or linked from [vietboost.net](https://vietboost.net).

SHA-256: `BC40D81E2E59B40EFDEA593A5D6007183D724A9C2BCEE752FB09027895B89E86`

### What changed in 1.1.14

- Refines the VIP trial surface into one compact, server-authoritative offer.
- Shows the trial only when the signed-in account is eligible on VietBoost.
- Opens the membership page for the full benefit review and secure claim flow.

## Version 1.1.13

Download [`vietboost-extension-1.1.13-chrome.zip`](./vietboost-extension-1.1.13-chrome.zip), then:

1. Extract the ZIP to a permanent folder on your computer.
2. Open `chrome://extensions` in Google Chrome.
3. Enable **Developer mode**.
4. Select **Load unpacked** and choose the extracted folder.

Check the [VietBoost changelog](https://vietboost.net/vi/changelog) before updating. Only use downloads published in this repository or linked from [vietboost.net](https://vietboost.net).

SHA-256: `F3B31A51A88FBE0C36F08C3000CBBA3B75F157329A5808CB3EEA6FDE24C1A2A5`

### What changed in 1.1.13

- Adds unified VIP membership management with monthly and annual plans.
- Adds configurable one-time 3, 7, or 30-day VIP trials.
- Adds server-verified promotion-code checkout.
- Keeps account entitlement synchronized after a trial claim.

## Version 1.1.12

Download [`vietboost-extension-1.1.12-chrome.zip`](./vietboost-extension-1.1.12-chrome.zip), then:

1. Extract the ZIP to a permanent folder on your computer.
2. Open `chrome://extensions` in Google Chrome.
3. Enable **Developer mode**.
4. Select **Load unpacked** and choose the extracted folder.

Check the [VietBoost changelog](https://vietboost.net/vi/changelog) before updating. Only use downloads published in this repository or linked from [vietboost.net](https://vietboost.net).

SHA-256: `5204AE2EA4DCFD7AB64394C1A6977FECC18D5086C53E56078C783541CFA73253`

### What changed in 1.1.12

- Fixes Douyin scans that incorrectly returned zero media because image CDN URLs were rejected.
- Adds a dedicated Douyin scanner for public page media metadata, including blob-backed video playback.
- Standard accounts download the public standard-quality source; VIP unlocks the highest public source when available.
- Improves source selection for X images and video variants, reducing preview-quality downloads.
