# Quell — free HTML template with a working contact form

A one-page portfolio for an architect, a structural engineer or a small design studio, in a single index.html plus an img/ folder.

![Quell screenshot](./screenshot.png)

**Live demo:** https://quell.formgong.com · **Template page:** https://formgong.com/en/website-templates/quell/?utm_source=github&utm_medium=template&utm_campaign=quell-html

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/formgong-hq/quell-html)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/formgong-hq/quell-html)
[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/formgong-hq/quell-html)

## Features

- One-page, responsive, fonts bundled (no Google Fonts requests)
- Contact form that works without a server, powered by [Formgong](https://formgong.com/?utm_source=github&utm_medium=template&utm_campaign=quell-html&utm_content=features), a free form backend
- Spam protection (honeypot), success/error states from the real server answer
- Privacy page included · MIT licensed

## Quick start

Open `index.html`, or upload the folder to any static host (Cloudflare Pages, Netlify, GitHub Pages, shared hosting).

## Contact form via Formgong

The form posts straight to `https://formgong.com/submit`; no backend, no PHP, no serverless function.

The contact form posts to `https://formgong.com/submit`. No build step: it is one `index.html` with `assets/` and `img/`.

1. Create a form at https://formgong.com/new and copy its access key.
2. In `index.html`, replace `fk_your_access_key` with that key.
3. The form sends `access_key`, `subject`, `botcheck`, `name`, `email`, `project`, `location`, `timing`, `message`. The page shows thanks only when Formgong answers `success: true`.

Submissions arrive by email (and optionally Telegram, Slack or Discord). Formgong has a free plan: [create a free form](https://formgong.com/?utm_source=github&utm_medium=template&utm_campaign=quell-html&utm_content=form-setup).

## Deploy

Build command: `no build step` · Output directory: `. (repository root)`. Works on Netlify, Vercel, Cloudflare and any static host.

## Files


```
assets/
  fonts/
    archivo-normal-100-900-62125-latin-ext.woff2
    archivo-normal-100-900-62125-latin.woff2
    OFL-Archivo.txt
  site.css
  site.js
img/  (15 files)
index.html
LICENSE
```

## Images

The photos were generated for this template (ChatGPT image generation, OpenAI). The places and people are fictional. Replace them with your own before launch.

## Fonts

Archivo: bundled as WOFF2 files (Latin and Latin Extended), no requests to Google Fonts. SIL Open Font License 1.1, the licence texts are next to the font files.

MIT license.

## License

MIT © Formgong. Demo names, texts and photos are fictional sample content. Questions: support@formgong.com
