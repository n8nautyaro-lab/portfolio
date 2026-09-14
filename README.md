# suslovautomation.com

Personal portfolio — Yaroslav Suslov, Automation & AI Engineer (Toronto, ON).

Static site, no build step. `index.html` is self-contained: all CSS and JS are inline,
fonts come from Google Fonts, and the favicon is an inline SVG data URI.

## Files

| File | Purpose |
|---|---|
| `index.html` | the whole site |
| `og.png` | 1200×630 link preview (LinkedIn, Slack, Telegram) |
| `CNAME` | custom domain for GitHub Pages |
| `robots.txt`, `sitemap.xml` | indexing |

## Local preview

    python3 -m http.server 8000

Then open http://127.0.0.1:8000

## Deploy

Push to `main`. GitHub Pages serves the repository root.
