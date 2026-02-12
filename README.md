# language-of-desire-library

GitHub Pages static one-page site for the Language of Desire library.

## Preview locally

```bash
python3 -m http.server 8000
```

Open http://localhost:8000

## Publish on GitHub Pages

This repository deploys with **GitHub Actions** using `.github/workflows/static.yml`.

## Affiliate link placeholder

Paste the affiliate link by replacing `HOPLINK_GOES_HERE` in `index.html`.

## Deployment sanity checks

Before or after a deploy, confirm:

- `index.html` exists at repository root.
- Workflow file exists with a valid extension: `.github/workflows/static.yml`.
- `.nojekyll` exists at repository root.
- Workflow uploads repository root as the Pages artifact (`path: .`).

To manually re-run deployment:

1. Go to **Actions**.
2. Open **Deploy static content to Pages**.
3. Click **Run workflow**.
