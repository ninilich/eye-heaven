# EyeHeaven — Landing Page

Landing page for the [EyeHeaven](https://github.com/ninilich/eye-heaven-app) macOS app, hosted via GitHub Pages.

## Structure

| File | Description |
|------|-------------|
| `index.html` | Main landing page |
| `icon.png` | App icon |
| `screenshot-*.jpg` | App screenshots |

## Hosting

Published at: **https://ninilich.github.io/eye-heaven/**

Enabled via: Repository Settings → Pages → Branch `main` / root.

## App Store URLs

When submitting to App Store Connect:

- **Support URL**: `https://ninilich.github.io/eye-heaven/`
- **Marketing URL**: `https://ninilich.github.io/eye-heaven/`
- **Privacy Policy URL**: `https://github.com/ninilich/eye-heaven-app/blob/main/PRIVACY.md`

## Updating the App Store link

When the app is published, replace the two `Coming Soon` placeholders in `index.html`:

1. `btn-appstore-disabled` in the hero section
2. `btn-appstore-cta` in the CTA section

Replace both with a real link using the same markup as in [boring-meeting](https://github.com/ninilich/boring-meeting).
