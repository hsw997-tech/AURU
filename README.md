
# AURU — Static Website (Deploy-Ready)

This is a minimal, design-forward static site for a handcrafted jewelry brand.

## Files
- `index.html` — home
- `shop.html` — placeholder shop grid (map to products when migrating to Shopify)
- `about.html` — brand story
- `contact.html`
- `legal-impressum.html`, `legal-privacy.html`, `legal-returns.html` — German legal pages
- `styles.css`
- `assets/` — place your images here

## Quick Deploy (GitHub Pages)
1. Create a new repo on GitHub, name it e.g. `auru-site`.
2. Upload all files from this folder.
3. Go to **Settings → Pages → Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: `main` / root (`/`)
4. Save. Your site will be live at `https://YOUR-USER.github.io/auru-site/`.

## Quick Deploy (Netlify)
1. Go to https://app.netlify.com/drop
2. Drag & drop this folder (or the ZIP). Netlify gives you a public `*.netlify.app` link instantly.

## Migrate to Shopify
- Use this static site as visual/content reference. 
- In Shopify, select a theme (Craft/Studio), then recreate sections using these texts and images.
- Add payments (PayPal, Klarna, Stripe) and shipping (DHL/Hermes) from Shopify Settings and Apps.
