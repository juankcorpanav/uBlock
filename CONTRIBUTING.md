# Contributions

Please refer to the sections below to find the appropriate destination for your contributions. Thank you for your support!

---

### Translations

You can help translate uBO via [Crowdin](https://crowdin.com/project/ublock).

---

### Reporting Issues

The issue tracker in this repository is deprecated. Use the links below to report your issues.

#### Support Forum

For support, questions, or assistance, please visit [/r/uBlockOrigin](https://www.reddit.com/r/uBlockOrigin/).

#### Filter List Issues

Report issues related to filter lists or broken website functionality in the [uAssets issue tracker](https://github.com/uBlockOrigin/uAssets/issues).

#### uBlock Origin (uBO) Issues

For issues specifically about uBO, please use the [uBO issue tracker](https://github.com/uBlockOrigin/uBlock-issues/issues).

#### uBO Lite (uBOL) Issues

For issues related to the Manifest Version 3 (MV3) variant, report them in the [uBOL issue tracker](https://github.com/uBlockOrigin/uBOL-home/issues).

---

### Personal Notes (Fork)

> **Note:** This is a personal fork for learning and experimentation. Changes here are not intended for upstream contribution. For reference, the upstream project lives at [gorhill/uBlock](https://github.com/gorhill/uBlock).

#### Local Development Setup

Quick reference for getting this fork running locally:

1. Clone the repo and load it as an unpacked extension in `chrome://extensions` (enable Developer Mode first).
2. After making changes, click the refresh icon on the extension card to reload.
3. Use `about:blank` with the extension popup open to test changes without side effects from page content.

#### Useful Debug Tips

- Open the extension's background page via `chrome://extensions` → "service worker" (MV3) or "background page" (MV2) to access the console.
- Filtering logs are available in the uBO logger (the icon that looks like a scroll in the popup).
- When testing filter rules, use the logger to confirm whether a rule is actually matching.
- To quickly reset all settings to default during testing, go to the Dashboard → Settings → "Reset to default settings". Useful when a config change causes unexpected behavior.

#### Branches in This Fork

- `main` — tracks upstream as closely as possible
- `personal` — my working branch with any local tweaks or experiments
