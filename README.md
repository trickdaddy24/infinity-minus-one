<div align="center">

# Infinity Minus One

**A single-page static site (`index.html` + images) — no build step, deploy anywhere.**

[![License: MIT](https://img.shields.io/badge/license-MIT-22c55e?style=flat-square)](LICENSE)
[![Version](https://img.shields.io/badge/version-0.1.0-8A4DFF?style=flat-square)](CHANGELOG.md)
[![Static](https://img.shields.io/badge/static-HTML-E34F26?style=flat-square&logo=html5&logoColor=white)](index.html)

</div>

## Table of Contents

- [Overview](#overview)
- [Structure](#structure)
- [Quick Start](#quick-start)
- [Deployment](#deployment)
- [Roadmap](#roadmap)
- [Version History](#version-history)
- [License](#license)

## Overview

A self-contained static page — everything lives in `index.html` with assets in
`images/`. No framework, bundler, or build step.

## Structure

```
infinity-minus-one/
├── index.html      # the page (markup + styles/scripts inline or linked)
├── images/         # static assets referenced by the page
├── VERSION
└── LICENSE
```

## Quick Start

```bash
# just open it
open index.html            # macOS  (Windows: start index.html)

# or serve locally
python -m http.server 8080   # → http://localhost:8080
```

## Deployment

It's a static site — host the folder anywhere: **Cloudflare Pages**, GitHub Pages,
Netlify, or any static file server. For Cloudflare Pages, point the project at this repo
with no build command and the root as the output directory.

## Roadmap

- [ ] Confirm/wire the production domain and host (Cloudflare Pages).
- [ ] Add a screenshot/preview to this README.
- [ ] Extract inline styles/scripts if the page grows.

## Version History

| Version | Date | Highlights |
|---|---|---|
| 0.1.0 | 2026-06-01 | Initial documented baseline (static single-page site). |

See [CHANGELOG.md](CHANGELOG.md).

## License

[MIT](LICENSE) © Minus One Labs
