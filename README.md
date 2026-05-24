# uBlock

A fork of [gorhill/uBlock](https://github.com/gorhill/uBlock) — an efficient blocker for browsers.

[![License](https://img.shields.io/badge/License-GPLv3-blue.svg)](LICENSE.txt)

## Overview

uBlock is a wide-spectrum content blocker with CPU and memory efficiency as primary features. This fork aims to maintain compatibility with the upstream project while introducing additional improvements and fixes.

## Features

- Efficient network request filtering
- Cosmetic filtering (element hiding)
- Script injection blocking
- Support for multiple filter list formats (Adblock Plus, uBlock Origin, hosts files)
- Low memory and CPU footprint
- No monetization, no "acceptable ads"

## Installation

### From Source

1. Clone this repository:
   ```bash
   git clone --recurse-submodules https://github.com/yourusername/uBlock.git
   ```

2. Open your browser's extension management page:
   - **Chrome/Chromium**: `chrome://extensions/`
   - **Firefox**: `about:debugging#/runtime/this-firefox`
   - **Edge**: `edge://extensions/`

3. Enable **Developer mode**.

4. Click **Load unpacked** (Chrome/Edge) or **Load Temporary Add-on** (Firefox) and select the `src` directory.

## Building

Prerequisites: Node.js 16+

```bash
npm install
npm run build
```

Build artifacts will be placed in the `dist/` directory.

## Personal Notes

> These are my own notes for working with this fork locally.

- I primarily use this on Firefox and Chrome for testing.
- To quickly reload the extension during development, use the browser's extension page refresh button rather than restarting the browser.
- Useful for debugging: open the background page devtools via the extension management page.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting pull requests.

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for a list of changes.

## License

This project is licensed under the GNU General Public License v3.0 — see [LICENSE.txt](LICENSE.txt) for details.

## Acknowledgements

- [gorhill](https://github.com/gorhill) for the original uBlock Origin project
- All contributors and filter list maintainers
