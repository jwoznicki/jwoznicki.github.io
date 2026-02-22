# Detroit Analytics LLC Website

Simple one-page GitHub Pages site for `detroitanalyticsllc.com`.

## Files

- `index.html`: landing page content
- `styles.css`: site styling
- `CNAME`: custom domain for GitHub Pages

## Deploy on GitHub Pages

1. Push this repository to GitHub.
2. In the repository settings, open **Pages**.
3. Set **Source** to `Deploy from a branch`.
4. Choose `main` branch and `/ (root)`, then save.
5. Confirm the custom domain is `detroitanalyticsllc.com`.

## DNS Setup for `detroitanalyticsllc.com`

At your domain registrar, configure:

- `A` records for `@` pointing to:
  - `185.199.108.153`
  - `185.199.109.153`
  - `185.199.110.153`
  - `185.199.111.153`
- `CNAME` record for `www` pointing to: `jwoznicki.github.io`

DNS changes can take time to propagate. Once records propagate, enable **Enforce HTTPS** in GitHub Pages settings.
