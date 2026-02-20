# BQueen Beauty Website

This repository contains a static landing page for a women's beauty products store inspired by modern beauty-commerce layouts.

The page highlights:
- Hero offer banner
- Shop-by-category cards (Makeup, Skincare, Haircare, Fragrances, Nails, Bath & Body)
- Trending product picks
- Daily offer table
- Popular brands strip

## Deployment

This repo is configured to deploy automatically to **GitHub Pages** using:

- `.github/workflows/deploy.yml`

### One-time setup in GitHub

1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Push changes to the `work` branch (or run the workflow manually from the **Actions** tab).

After deployment, GitHub provides the live URL in the workflow run summary.

## Local preview

```bash
python3 -m http.server 4173
```

Open:
- `http://localhost:4173`
