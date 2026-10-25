# Vāk Website

Standalone responsive static website, separate from the Windows app repository.

## Pages
- `index.html` — homepage
- `features.html` — feature overview
- `about.html` — about Vāk
- `support.html` — support and release status
- `privacy-policy.html` — Vāk V1 privacy policy

## Preview
Open `index.html` in a browser, or run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Deploy
Upload the contents of this folder to the web root for `vak.lordk22.in`. Enable HTTPS. Configure `/privacy-policy` to serve or redirect to `privacy-policy.html` (or move that file to `privacy-policy/index.html`).

## Before publishing
1. Confirm the policy dates and compare the policy with the exact release build.
2. Add the official Microsoft Store listing URL once the listing is public.
3. Verify the privacy page is publicly accessible over HTTPS.
4. Test desktop and mobile layouts.

No analytics scripts are included. Google Fonts are loaded remotely; remove the `@import` line in `assets/styles.css` if you want to avoid that third-party font request. The privacy policy is a product disclosure draft, not legal advice.


## Branding assets
The site uses the supplied Vāk brand pack in `assets/brand/`:
- `vak-logo-dark.svg` for the dark site header/footer and mockup
- `vak-symbol.svg` for the mockup's symbol
- `vak-icon-32.png` for the favicon
- `vak-logo-light.svg` and black symbol are included for alternate backgrounds
