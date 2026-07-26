# VietBoost Extension Downloads

This repository contains the official packaged downloads for the VietBoost Chrome extension. The VietBoost website and source repository remain private.

## Version 1.1.1

Download [`vietboost-extension-1.1.1-chrome.zip`](./vietboost-extension-1.1.1-chrome.zip), then:

1. Extract the ZIP to a permanent folder on your computer.
2. Open `chrome://extensions` in Google Chrome.
3. Enable **Developer mode**.
4. Select **Load unpacked** and choose the extracted folder.

Check the [VietBoost changelog](https://vietboost.net/vi/changelog) before updating. Only use downloads published in this repository or linked from [vietboost.net](https://vietboost.net).

SHA-256: `7425B1C062459055BBA79BC2DD5E51E7D828ABE6BCD9A95205F20BFB565F1126`

### What changed in 1.1.1

- Fix account linking for the manual package by using one stable Chrome extension identity.
- Improve production authentication safety by allowing only that identity to call protected extension APIs.
