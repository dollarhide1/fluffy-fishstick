# RN at 50 — Your Nursing Journey Starter Kit (landing page)

A single-page sales site for **The Mature RN**'s $97 Starter Kit bundle by Carol Lee.

- **`index.html`** — the entire site. Self-contained (all CSS, icons, and fonts-via-CDN are inline). No build step, no dependencies.
- Buy buttons link to the Payhip bundle: `https://payhip.com/b/PXdSl`

## Deploy

**Netlify (drag-and-drop):** drag this folder onto the "Deploy manually" box at app.netlify.com.

**Netlify (from GitHub):** push this repo to GitHub, then in Netlify choose *Add new site → Import from Git*, pick the repo, and deploy. No build command needed — Netlify serves `index.html` automatically. Publish directory: repo root.

## Updating

Edit `index.html` and re-deploy (or push to GitHub if using continuous deploy). To change the checkout link, find `payhip.com/b/PXdSl` (appears twice) and replace it.
