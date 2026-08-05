<div align="center">

# Scale Dev Tools

**JSON · YAML · CSV · XML conversion, JWT decoding, hashing, regex and more — entirely in your browser.**

[**→ Open Scale Dev Tools**](https://jasminder-chhabra.github.io/scale-dev-tools/)

<img src="https://img.shields.io/badge/license-MIT-7C3AED?style=for-the-badge" alt="MIT">
<img src="https://img.shields.io/badge/dependencies-1-1B1530?style=for-the-badge" alt="One dependency">
<img src="https://img.shields.io/badge/works-offline-059669?style=for-the-badge" alt="Offline">

</div>

---

## Why

Pasting a production JWT or an API payload into a random online decoder means handing it to someone else's server. Every tool here runs as JavaScript on your own machine — there is no backend, and no network call is made at runtime. Turn off your Wi-Fi and it still works.

## The tools

| Tool | What it does |
|---|---|
| **JSON · YAML · CSV · XML** | Convert between all four, with automatic format detection. RFC 4180 CSV — quoted commas, escaped quotes and embedded newlines all survive a round trip |
| **JWT decoder** | Header, payload and expiry status. Never asks for your signing secret |
| **Hashes** | SHA-1, SHA-256, SHA-384, SHA-512 via WebCrypto |
| **UUID** | RFC 4122 v4 in bulk, four output formats |
| **Regex tester** | Live highlighting and capture groups, with a zero-length-match guard |
| **URL encode/decode** | Component-level, the one you want for query values |
| **Timestamp** | Unix seconds or milliseconds ⇄ UTC, local and relative time |
| **Diff** | Line-by-line LCS comparison with add/remove counts |
| **Cron** | Plain-English explanation of a five-field expression, with range validation |
| **Colour** | HEX ⇄ RGB ⇄ HSL with a live swatch |
| **Case & slug** | camel, Pascal, snake, kebab, CONSTANT, Title and URL slug |

## Privacy

No servers, no analytics, no cookies, no telemetry. The single dependency ([js-yaml](https://github.com/nodeca/js-yaml), MIT) is vendored into `vendor/` rather than loaded from a CDN, and the brand fonts are self-hosted — so nothing phones home.

## Part of a set

- [Scale Tools](https://github.com/Jasminder-Chhabra/scale-tools) — PDF and everyday utilities
- [Scale Image Tools](https://github.com/Jasminder-Chhabra/scale-image-tools) — image manipulation
- [Scale SEO Tools](https://github.com/Jasminder-Chhabra/scale-seo-tools) — SEO and business

## Licence

MIT.

---

<div align="center">
<sub>Built and given away by <a href="https://scaleus.in">Scale Us Technologies</a>.</sub>
</div>
