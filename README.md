# VietBoost Extension Downloads

This repository contains the official packaged downloads for the VietBoost Chrome extension. The VietBoost website and source repository remain private.

## Version 1.1.20

Download [`vietboost-extension-1.1.20-chrome.zip`](./vietboost-extension-1.1.20-chrome.zip), then:

1. Extract the ZIP to a permanent folder on your computer.
2. Open `chrome://extensions` in Google Chrome.
3. Enable **Developer mode**.
4. Select **Load unpacked** and choose the extracted folder.

SHA-256: `71D32FFA147F87A48B7D5DE3625C87D601693B59516023F9B33D1F6661500C7B`

### What changed in 1.1.20

- Unifies the daily download quota across supported platforms: guest 10, signed-in 100, VIP unlimited; bulk download and image/video conversion limits are separately configurable by an administrator.
- Shows the true device activity update time and keeps popup, page toast, slide panel, and options language in sync after switching Vietnamese or English.
- Lets administrators select only approved current OpenAI, Google Gemini, or DeepSeek models; the extension receives the same enabled provider/model metadata through the authenticated API.
- Makes active public VIP promotion codes visible on the purchase flow and applies a shared or term-specific code server-side before payment.

## Version 1.1.19

Download [`vietboost-extension-1.1.19-chrome.zip`](./vietboost-extension-1.1.19-chrome.zip), then:

1. Extract the ZIP to a permanent folder on your computer.
2. Open `chrome://extensions` in Google Chrome.
3. Enable **Developer mode**.
4. Select **Load unpacked** and choose the extracted folder.

SHA-256: `BE021484B371BCA822778C9DE6D2006B0656FF45DA50A35B80E4A8ECF5A5166B`

### What changed in 1.1.19

- Carries the selected Vietnamese or English language into page toasts, including scan and download progress.
- Adds a compact live activity and quota surface for guest, signed-in, and VIP sessions; completed downloads are shown for the current Chrome profile, while the VIP system-AI meter remains account-authoritative.
- Rebuilds the **Your API key** workspace with the official OpenAI, Google Gemini, and DeepSeek logos and clear per-provider status.

## Version 1.1.18

Download [`vietboost-extension-1.1.18-chrome.zip`](./vietboost-extension-1.1.18-chrome.zip), then:

1. Extract the ZIP to a permanent folder on your computer.
2. Open `chrome://extensions` in Google Chrome.
3. Enable **Developer mode**.
4. Select **Load unpacked** and choose the extracted folder.

SHA-256: `625D3CB837743224D8E07C45FD40F825B3091A6EF8DDEBB824C84DA4FBDB37FC`

### What changed in 1.1.18

- Preserves the signed-in device across future extension updates by restoring a fresh short-lived access token from the trusted persisted refresh session.
- Adds a restrained Chrome Web Store review prompt after real usage: three completed downloads and seven days of use, with a 45-day snooze and no repeat after rating.
- Sends installation and update CTAs to the official Chrome Web Store listing.

## Version 1.1.17

Download [`vietboost-extension-1.1.17-chrome.zip`](./vietboost-extension-1.1.17-chrome.zip), then:

1. Extract the ZIP to a permanent folder on your computer.
2. Open `chrome://extensions` in Google Chrome.
3. Enable **Developer mode**.
4. Select **Load unpacked** and choose the extracted folder.

SHA-256: `F17BF93106B909E782992F47B0F9AAE585C7B9685852A762887D88233E11F9FE`

### What changed in 1.1.17

- Uses the bundled OpenAI, Google Gemini, and DeepSeek marks in a clearer AI settings workspace.
- Shows a real per-account daily system-AI meter from VietBoost instead of a client-side estimate.
- Keeps the secure VietBoost system model and browser-local personal API key as distinct, clearly labelled choices.
- Adds a responsive admin workspace frame so operational panels and forms keep consistent spacing away from the sidebar.

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
