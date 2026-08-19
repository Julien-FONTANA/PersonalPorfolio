# Portfolio — Fontana Julien

[![Live](https://img.shields.io/badge/live-personal--porfolio.vercel.app-5b5fe9?style=flat-square&logo=vercel&logoColor=white)](https://personal-porfolio-eight-hazel.vercel.app/)
[![Static HTML](https://img.shields.io/badge/stack-static%20HTML-e34f26?style=flat-square&logo=html5&logoColor=white)](Portfolio.dc.html)
![No build step](https://img.shields.io/badge/build-none-4c1?style=flat-square)
![FR | EN](https://img.shields.io/badge/i18n-FR%20%7C%20EN-5b5fe9?style=flat-square)
[![Last commit](https://img.shields.io/github/last-commit/Julien-FONTANA/PersonalPorfolio?style=flat-square)](https://github.com/Julien-FONTANA/PersonalPorfolio/commits/main)

Single-page personal portfolio — Technical Lead, Engineering Manager, architecte .NET.
Bilingual FR/EN via the flag toggle in the header.

## Files

| | |
|---|---|
| `Portfolio.dc.html` | The entire site — markup, styles and content in one Claude Design canvas |
| `support.js` | Canvas runtime; pulls React from unpkg and renders client-side |
| `vercel.json` | Rewrites `/` to `Portfolio.dc.html` |
| `docs/` `uploads/` `scraps/` | Photos, project screenshots, CV |

## Preview locally

```bash
python -m http.server 4321
```

Then open <http://localhost:4321/Portfolio.dc.html>.

## Deploy

Push to `main`; Vercel redeploys automatically. Application preset **Other** — no build command, no install command, output directory at the repo root.
