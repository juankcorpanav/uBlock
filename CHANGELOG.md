- [Add ISO-8859-2 as alias of Windows-1250 in text encoder](https://github.com/gorhill/uBlock/commit/3f0c4e1110)

----------

# 1.70.1

- [Improve `freeze-element-property` scriptlet](https://github.com/gorhill/uBlock/commit/b91798c6f4)
- [Add support for network filter option `top=`](https://github.com/gorhill/uBlock/commit/aebc108e36)
- [Fix JS code extraction from web accessible resources](https://github.com/gorhill/uBlock/commit/a8bbd1a466)
- [Add `freeze-element-property` scriptlet](https://github.com/gorhill/uBlock/commit/05f01f6be4)
- [chromium][Categorize `.svg` resources as image type](https://github.com/gorhill/uBlock/commit/b862b73134)
- [Add `prevent-navigation` scriptlet](https://github.com/gorhill/uBlock/commit/60f57594bf)
- [Fix editor's autocomplete for first filter option](https://github.com/gorhill/uBlock/commit/ab8baaf833)
- [Add new filter option: `requestheader`](https://github.com/gorhill/uBlock/commit/e871d6e673)
- [Minor improvement of `trusted-create-html` scriptlet](https://github.com/gorhill/uBlock/commit/527939854d)

----------

# 1.70.0

- [Improve `json-edit`-related scriptlets](https://github.com/gorhill/uBlock/commit/98d3e9500a)
- [Improve `trusted-create-html` scriptlet](https://github.com/gorhill/uBlock/commit/baffd32dab)
- [Improve `prevent-fetch` scriptlet](https://github.com/gorhill/uBlock/commit/2ce376cf1d)
- [Fix handling of `extraMatch` parameter in `trusted-click-element` scriptlet](https://github.com/gorhill/uBlock/commit/a8ad95394d)
- [Improve `generateContentFn` helper scriptlet](https://github.com/gorhill/uBlock/commit/7d95c58408)
- [Improve `prevent-xhr` scriptlet](https://github.com/gorhill/uBlock/commit/168394440c)
- [Improve `proxyApplyFn` helper scriptlet](https://github.com/gorhill/uBlock/commit/18a8fc7675)

----------

# 1.69.0

- [Add `adthrive` shim](https://github.com/gorhill/uBlock/commit/b8bf0bbab4)
- [Add `elem.shadowRoot` fallback in `getShadowRoot`](https://github.com/gorhill/uBlock/commit/c8b42ea819) (by @antonok-edm)
- [Fix merging of uncommitted filters](https://github.com/gorhill/uBlock/commit/c8004c4b02)
- [Improve `urlskip` implementation](https://github.com/gorhill/uBlock/commit/41ced43f03)
- [Improve `set-attr`/`trusted-set-attr` scriptlets](https://github.com/gorhill/uBlock/commit/3f3d4768b6)
- [Improve `trusted-create-html` scriptlet](https://github.com/gorhill/uBlock/commit/3c7eb3497d)
- [Add Anti-AI Suggestions list](https://github.com/gorhill/uBlock/commit/a0a7a99675) (by @ryanbr)
- [Unescape unduly escaped `|` in regex-based domain options](https://github.com/gorhill/uBlock/commit/bb34a4b83b)
- [Mind id/class changes in generic cosmetic filtering surveyor](https://github.com/gorhill/uBlock/commit/c053361d30)
- [Fix `specifichide` option](https://github.com/gorhill/uBlock/commit/024019094f)
- [Improve `prevent-addEventListener` scriptlet](https://github.com/gorhill/uBlock/commit/1977196abe)
- [Add `nitropay_ads.js` shim](https://github.com/gorhill/uBlock/commit/6af8a457ed)

<!-- Personal note: tracking 1.69.0 closely — the `trusted-click-element` extraMatch fix and
     `prevent-addEventListener` improvement both address issues I was hitting on a few sites. -->
