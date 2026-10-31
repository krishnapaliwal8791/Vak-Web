# Vāk Website

Official responsive website for Vāk — Voice-to-Text for Windows.

## Microsoft Store Listing
- **Listing URL:** https://apps.microsoft.com/detail/9MZ5MB2W0DFN?hl=en-us&gl=IN&ocid=pdpshare
- **Platform:** Windows 10 / Windows 11 (64-bit)
- **Status:** Officially Released & Publicly Available

## Pages
- `index.html` — Homepage with hero, features overview, workflow, and Microsoft Store download section
- `features.html` — Comprehensive feature overview (speech-to-text, hotkey activation, local processing, VAD, model choices, text injection)
- `about.html` — About Vāk and developer background
- `support.html` — Support resources, troubleshooting guide, and release status
- `privacy-policy.html` — Vāk V1 privacy policy & local data disclosures

## Local Preview
Open `index.html` in any browser, or run a local web server:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.

## Deploy
Upload the contents of this repository to the web root for `vak.lordk22.in`. Ensure HTTPS is enabled. Configure `/privacy-policy` to serve or redirect to `privacy-policy.html`.

## Branding assets
The site uses the Vāk brand assets located in `assets/brand/`:
- `vak-logo-dark.svg` — Primary dark theme logo for header, footer, and mockup
- `vak-symbol.svg` — Primary brand symbol
- `vak-icon-32.png` — 32x32 favicon
- `vak-icon-256.png` — High-resolution app icon used for Open Graph and Twitter cards
- `vak-logo-light.svg` & `vak-symbol-black.svg` — Alternate brand assets
