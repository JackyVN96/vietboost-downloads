# VietBoost Extension Downloads

This repository contains the official packaged downloads for the VietBoost Chrome extension. The VietBoost website and source repository remain private.

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
