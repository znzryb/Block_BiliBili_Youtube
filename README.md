# Block BiliBili YouTube

A minimal Chrome extension that blocks access to Bilibili and YouTube.

## Blocked Sites

- `bilibili.com`
- `youtube.com`
- `youtu.be`

## Install Locally

1. Open `chrome://extensions/`.
2. Enable Developer mode.
3. Click Load unpacked.
4. Select this repository folder.

The extension uses Manifest V3 `declarativeNetRequest` rules to block top-level and embedded page loads for the listed domains.
