# BunMixer Public Site

This repository contains the static public pages for BunMixer.

## GitHub Pages

Publish from the repository root:

- Home: `index.html`
- Privacy Policy URL: `privacy.html`
- Support URL: `support.html`
- Jekyll bypass marker: `.nojekyll`

The privacy and support pages include English, Korean, Japanese, Simplified Chinese, Traditional Chinese, Spanish, German, and French sections in the same page.

After GitHub Pages is enabled, the default URLs should be:

- `https://facta-leopard.github.io/BunMixer/`
- `https://facta-leopard.github.io/BunMixer/privacy.html`
- `https://facta-leopard.github.io/BunMixer/support.html`

Recommended GitHub Pages settings:

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/ (root)`

If branch publishing is unavailable, use the included GitHub Actions workflow:

- Source: GitHub Actions
- Workflow: `Deploy BunMixer public site`

Do not finalize App Store metadata while these URLs return 404. After all three
URLs return HTTP 2xx, use the privacy and support URLs above in App Store
Connect.
