# Engineer.ai

Static "domain for sale" landing page for Engineer.ai. Plain HTML and CSS, no build step, no JavaScript.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole page, with inline CSS, SEO meta tags and JSON-LD (Product, Offer, FAQPage) |
| `favicon.svg`, `apple-touch-icon.png` | Beam E icon |
| `og-image.png` | 1200x630 social share image |
| `assets/` | QQuantum.ai and Coherence footer logos |
| `robots.txt`, `sitemap.xml`, `llms.txt` | Crawler and LLM discovery |

## Contact

- Every call to action opens an email to `team@coherence.com`.

## Hosting

Upload the folder as-is to any static host (GitHub Pages, Cloudflare Pages, Netlify, S3). For GitHub Pages, enable Pages on the `main` branch root and point the Engineer.ai DNS at it.

## Preview locally

```bash
python3 -m http.server 8000
```
