![License](https://img.shields.io/badge/License-MIT-blue) ![Release](https://img.shields.io/badge/Release-2.0.0-blue)
# Pekadi's YouTube Ad Blocker

My YouTube Ad Blocker is a powerful ***Chrome, Opera - Opera GX*** extension designed to block intrusive ads on YouTube. It eliminates skip-able ads, non-skip-able ads, sponsor segments, and overlay ads, enhancing your YouTube viewing experience. This extension runs in the background to ensure seamless ad-free playback without requiring manual intervention.


# Browser Support

| <a href="https://www.google.com/chrome/"><img src="./logos/chrome.svg" width="42px" /><br /><span>Chrome</span></a> | <a href="https://www.microsoft.com/edge"><img src="./logos/edge.svg" width="42px" /><br /><span>Edge</span></a> | <a href="https://www.opera.com/"><img src="./logos/opera.svg" width="42px" /><br /><span>Opera</span></a> | <a href="https://www.opera.com/gx"><img src="./logos/operagx.svg" width="42px" /><br /><span>Opera GX</span></a> |
| ---- | ---- | ---- | ---- |


# Features
> [!TIP]
> - Removes skip-able and non-skip-able ads.
> **Sponsor block:**
> - Blocks sponsor content and overlays.
> **Dynamic ad removal:**
> - Monitors and blocks dynamically loaded ads during video playback.
> **Lightweight:**
> - Minimal performance impact while blocking ads effectively.
> **Custom rules:**
> - Configured to target YouTube and related domains (e.g., DoubleClick and Google Video).

# Installation
> [!IMPORTANT]
> 1. Clone or download this repository.
> 2. Open Chrome (or a Chromium-based browser like Opera).
> 3. Go to `chrome://extensions/` or `opera://extensions/`.
> 4. Enable **Developer mode** (toggle in the top-right corner).
> 5. Click **Load unpacked** and select the downloaded folder containing the extension files.
> 6. For any reason a ad does pop up just click CLt + R!

## How It Works
The extension uses:
- **Declarative Net Request API**: Blocks network requests for ads at the browser level.
- **Content scripts**: Observes and removes ads dynamically injected into the DOM.
- **Service worker**: Keeps the extension active and ensures continuous functionality.


## Contributing
Feel free to contribute to this project by opening an issue or submitting a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
