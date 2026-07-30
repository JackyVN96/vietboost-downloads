# VietBoost Extension Downloads

This repository contains the official packaged downloads for the VietBoost Chrome extension. The VietBoost website and source repository remain private.

## Version 1.1.33

Download [`vietboost-extension-1.1.33-chrome.zip`](./vietboost-extension-1.1.33-chrome.zip), then:

1. Extract the ZIP to a permanent folder on your computer.
2. Open `chrome://extensions` in Google Chrome.
3. Enable **Developer mode**.
4. Remove the previous unpacked package, then select **Load unpacked** and choose the newly extracted folder.

SHA-256: `FB57C6A31E497A30288B128757AED87FBA39164E4B3D5CAE3A5C308ED9122CCE`

### What changed in 1.1.33

- Keeps Quick Action compact when a page loads, even when media is already detected or an older saved pin state exists.
- Decouples compact toast notifications from the full Quick Action panel so notifications no longer expand the workspace.
- Opens the panel temporarily on hover with automatic pointer-leave collapse, while explicit clicks and the current-page pin remain under user control.

## Version 1.1.32

Download [`vietboost-extension-1.1.32-chrome.zip`](./vietboost-extension-1.1.32-chrome.zip), then:

1. Extract the ZIP to a permanent folder on your computer.
2. Open `chrome://extensions` in Google Chrome.
3. Enable **Developer mode**.
4. Remove the previous unpacked package, then select **Load unpacked** and choose the newly extracted folder.

SHA-256: `D912E24D1D72A83D1A21EC318B63B547FA2984969B1DB77ED0DE0842DF4BCBAC`

### What changed in 1.1.32

- Restores automatic Quick Action and toast availability on ordinary HTTP/HTTPS websites through a safe runtime that does not install social route polling, selection actions, or hover-download hooks.
- Restores Chrome's **On all sites** permission choice while retaining the stable VietBoost extension identity.
- Adds compact conflict guidance to the popup, side panel, and relevant error toasts for diagnosing another active download extension.
- Uses the packaged VietBoost logo in Quick Action and extension-page toasts.
- Smooths Quick note hover expansion and automatically collapses it after the pointer or focus leaves.

## Version 1.1.31

Download [`vietboost-extension-1.1.31-chrome.zip`](./vietboost-extension-1.1.31-chrome.zip), then:

1. Extract the ZIP to a permanent folder on your computer.
2. Open `chrome://extensions` in Google Chrome.
3. Enable **Developer mode**.
4. Remove the previous unpacked package, then select **Load unpacked** and choose the newly extracted folder.

SHA-256: `47C2FD64A673C900EA7BA616CA6AE23A3AC6BFB880DC5ADD9D2DE2ECA642B372`

### What changed in 1.1.31

- Prevents passive popup status checks from injecting the full content runtime into ordinary websites.
- Requires exact social hostnames or real subdomains, so lookalike domains cannot activate social-page observers or overlays.
- Keeps ordinary websites free of persistent overlays, route polling, selection listeners, and hover handlers while preserving explicit one-time scans.
- Preserves the complete social capture experience on supported platforms and adds browser regression coverage for page images and extension overlays.

## Version 1.1.30

Download [`vietboost-extension-1.1.30-chrome.zip`](./vietboost-extension-1.1.30-chrome.zip), then:

1. Extract the ZIP to a permanent folder on your computer.
2. Open `chrome://extensions` in Google Chrome.
3. Enable **Developer mode**.
4. Remove the previous unpacked package, then select **Load unpacked** and choose the newly extracted folder.

SHA-256: `28B0A42EB3646FB6F28E60FC39577A1DF8935B45A28966D7D519A5F14AE779CC`

### What changed in 1.1.30

- Keeps ordinary websites passive by default so VietBoost does not mount persistent overlays, intercept clicks, poll routes, or delay page content.
- Preserves full social capture behavior on explicitly supported platforms, with manual one-time scanning still available on other pages through Chrome's `activeTab` permission.
- Rebuilds Saved content into a compact, searchable library with type counts, filters, sorting, collections, and clear numeric pagination.
- Adds a collapsible Quick note that opens on hover, compact saved cards, and stronger All, Link, Media, and Notes workflows.
- Removes popup module-preload warnings and external font requests while preserving the stable extension identity.

## Version 1.1.28

Download [`vietboost-extension-1.1.28-chrome.zip`](./vietboost-extension-1.1.28-chrome.zip), then:

1. Extract the ZIP to a permanent folder on your computer.
2. Open `chrome://extensions` in Google Chrome.
3. Enable **Developer mode**.
4. Select **Load unpacked** and choose the extracted folder.

SHA-256: `3D6EB182FC4DC2C869F53DDB6EFDD7117B680B55A14358A49B766AC52D7DA574`

### What changed in 1.1.28

- Synchronizes successful-download statistics with the signed-in VietBoost account independently of optional analytics consent.
- Separates successful files from quota reservations so extension and website usage totals are clear and auditable.
- Expands system-AI usage with the real daily reset time, completed requests, and token totals.
- Aligns extension account usage with the new VIP trial, upgrade, renewal, plan-change, and lifetime lifecycle.

## Version 1.1.27

Download [`vietboost-extension-1.1.27-chrome.zip`](./vietboost-extension-1.1.27-chrome.zip), then:

1. Extract the ZIP to a permanent folder on your computer.
2. Open `chrome://extensions` in Google Chrome.
3. Enable **Developer mode**.
4. Select **Load unpacked** and choose the extracted folder.

SHA-256: `6D73F69F9474F4E69694CAF7A65BA9C979ADAA840DDF5971B7A36B38EB437651`

### What changed in 1.1.27

- Preserves exact provider whitespace and CJK characters while streaming AI results instead of inserting spaces between tokens.
- Removes raw HTML and Markdown presentation markers before AI output is stored or shown.
- Adds translation targets for Vietnamese, English, Chinese, Korean, Japanese, Thai, Indonesian, and Filipino in page quick actions and the context menu.
- Works with the website's new automatic-plan-discount and voucher stacking rules.

## Version 1.1.26

Download [`vietboost-extension-1.1.26-chrome.zip`](./vietboost-extension-1.1.26-chrome.zip), then:

1. Extract the ZIP to a permanent folder on your computer.
2. Open `chrome://extensions` in Google Chrome.
3. Enable **Developer mode**.
4. Select **Load unpacked** and choose the extracted folder.

SHA-256: `1881300B468775D3F5D13A129CE800F7BE8F1814C37A4E5C99FC00813202B799`

### What changed in 1.1.26

- Replaces raw Markdown placeholders in Quick note with selection-aware list, task, quote, and labelled-link tools.
- Upgrades the on-page Saved content quick action with search, type filters, pagination, drag ordering, a formatting toolbar, and recent-note shortcuts.
- Automatically falls back to an enabled VietBoost AI provider when an older saved provider is unavailable, preventing translation actions from failing with a generic unavailable message.
- Keeps the AI provider selector aligned with the models that are currently enabled by the VietBoost server.

## Version 1.1.25

Download [`vietboost-extension-1.1.25-chrome.zip`](./vietboost-extension-1.1.25-chrome.zip), then:

1. Extract the ZIP to a permanent folder on your computer.
2. Open `chrome://extensions` in Google Chrome.
3. Enable **Developer mode**.
4. Select **Load unpacked** and choose the extracted folder.

SHA-256: `ED3C45ED42BE4F3D9AA337DE415B915EB0FDCB1A4DA0679B6CFD9572C67DC36F`

### What changed in 1.1.25

- Reads the visible extension version directly from the installed manifest so popup, panel, page quick action, and release UI cannot fall back to an old hard-coded version.
- Keeps the Qwen provider, Qwen logo, expanded Saved content workspace, and Quick note improvements introduced in 1.1.24.

## Version 1.1.24

Download [`vietboost-extension-1.1.24-chrome.zip`](./vietboost-extension-1.1.24-chrome.zip), then:

1. Extract the ZIP to a permanent folder on your computer.
2. Open `chrome://extensions` in Google Chrome.
3. Enable **Developer mode**.
4. Select **Load unpacked** and choose the extracted folder.

SHA-256: `4B53CD4EE94A47D41185B290A3BABC286900053CFA41140DD9E0E67C008865DA`

### What changed in 1.1.24

- Adds Alibaba Qwen as a first-class AI provider on VietBoost and in the extension, including the bundled Qwen logo, approved model selection, personal API-key mode, and server-side connection testing.
- Expands Saved content into a searchable, filterable, paginated card workspace with collections, tags, pin/status controls, editing, deletion, and cross-type drag-and-drop ordering.
- Improves Quick note with formatting shortcuts, labels, collection/status controls, and a direct path from the on-page quick action to the full saved-notes workspace.
- Extends page recognition and media scanning to regular websites while keeping account-backed library synchronization and locale state consistent across extension surfaces.

## Version 1.1.22

Download [`vietboost-extension-1.1.22-chrome.zip`](./vietboost-extension-1.1.22-chrome.zip), then:

1. Extract the ZIP to a permanent folder on your computer.
2. Open `chrome://extensions` in Google Chrome.
3. Enable **Developer mode**.
4. Select **Load unpacked** and choose the extracted folder.

SHA-256: `2C2A0C209F8F26B3EEC573B99204F63AAA9599CDEB43FAD5BE17AF4267A7A37B`

### What changed in 1.1.22

- Keeps the signed-in VietBoost account connected after a Chrome Web Store update by restoring the persisted refresh session without concurrent token rotation.
- Enforces signed-in download, bulk-download, and conversion quotas against the VietBoost account database; clearing extension storage no longer resets account usage.
- Adds compact Saved content, Scan media, and Quick note tabs to the on-page quick action.
- Keeps Vietnamese and English synchronized across popup, toast, page quick actions, scan controls, usage statistics, and device settings.

## Version 1.1.21

Download [`vietboost-extension-1.1.21-chrome.zip`](./vietboost-extension-1.1.21-chrome.zip), then:

1. Extract the ZIP to a permanent folder on your computer.
2. Open `chrome://extensions` in Google Chrome.
3. Enable **Developer mode**.
4. Select **Load unpacked** and choose the extracted folder.

SHA-256: `8AC94CC512738D486E50A20375DC1AC8098609C859657FAB513B67A320DE36C5`

### What changed in 1.1.21

- Keeps Vietnamese or English synchronized across popup, toast, page quick actions, scan results, tooltips, and settings while navigating between tabs.
- Localizes the on-page media scanner and download controls instead of falling back to Vietnamese after the popup is switched to English.
- Preserves toast locale listeners during action-chip remounts on dynamic social pages.
- Ships together with public-site social preview fixes and a safer one-time PayPal checkout flow.

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
