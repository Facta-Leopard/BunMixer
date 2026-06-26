# BunMixer Public Site

This repository contains the static public pages for BunMixer.

## GitHub Pages

Publish from the repository root:

- Home: `index.html`
- Privacy Policy URL: `privacy.html`
- Support URL: `support.html`

The privacy and support pages include English, Korean, Japanese, Simplified Chinese, Traditional Chinese, Spanish, German, and French sections in the same page.

After GitHub Pages is enabled, the default URLs should be:

- `https://facta-leopard.github.io/BunMixer/`
- `https://facta-leopard.github.io/BunMixer/privacy.html`
- `https://facta-leopard.github.io/BunMixer/support.html`

Recommended GitHub Pages settings:

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/ (root)`

Do not finalize App Store metadata while these URLs return 404. After all three URLs return HTTP 2xx, run:

```sh
Review/finalize_public_submission.sh \
  --privacy-url https://facta-leopard.github.io/BunMixer/privacy.html \
  --support-url https://facta-leopard.github.io/BunMixer/support.html \
  --check-remote
```
