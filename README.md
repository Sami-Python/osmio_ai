# Osmio AI – Company Website

Static company website for [osmioai.com](https://osmioai.com) — built with plain HTML, CSS, and vanilla JavaScript. Deployed via Cloudflare Pages.

## Structure

```
osmio_ai/
├── index.html      # Company homepage
├── styles.css      # Design system & styles
├── assets/         # Images and icons
└── README.md
```

## Deployment – Cloudflare Pages

1. Push this repository to GitHub
2. In Cloudflare Dashboard → Pages → Create a project
3. Connect your GitHub repo
4. Build settings:
   - **Build command:** *(leave empty)*
   - **Build output directory:** `/` (root)
5. Add custom domain: `osmioai.com`
6. Cloudflare auto-redeploys on every push to `main`

## Local Development

Just open `index.html` directly in a browser — no build step required.

Or with a local server:

```bash
# Python
python -m http.server 3000

# Node.js
npx serve .
```

Then visit `http://localhost:3000`.

---

© 2026 Osmio AI
