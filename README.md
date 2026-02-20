# BQueen Beauty Storefront

This repository contains a static women’s beauty ecommerce homepage inspired by modern beauty marketplace patterns.

## What's on the homepage

- Promotional top bar with offer messaging
- Navigation with category shortcuts
- Hero section with CTAs
- Beauty categories (Skincare, Makeup, Haircare, Fragrance)
- Best-seller product cards with pricing
- Offer highlights and customer reviews

## Deployment

This repo is configured to deploy automatically to **GitHub Pages** using:

- `.github/workflows/deploy.yml`

### One-time setup in GitHub

1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Push changes to `work`, `main`, or `master` (or run manually from **Actions**).

After deployment, GitHub displays the live URL in the workflow run summary.

## Local preview

```bash
python3 -m http.server 4173
```

Open:

- `http://localhost:4173`
