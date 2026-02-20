# BQueen Trading Products Website

This repository contains a static landing page that clearly showcases trading product categories (Stocks, Forex, Gold & Metals, Commodities, Indices, and Crypto).

## Deployment

This repo is configured to deploy automatically to **GitHub Pages** using the workflow at:

- `.github/workflows/deploy.yml`

### One-time setup in GitHub

1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Push changes to the `work` branch (or run the workflow manually from the **Actions** tab).

After deployment, GitHub provides the live URL in the workflow run summary.

## Local preview

Run a local server from the repo root:

```bash
python3 -m http.server 4173
```

Then open:

- `http://localhost:4173`
