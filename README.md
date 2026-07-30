# Frontage — frontagehq.studio

Static site hosted on GitHub Pages.

## Files
- index.html ......... the site (must keep this filename)
- favicon.png ........ browser tab icon
- apple-touch-icon.png iOS home-screen icon
- CNAME .............. custom domain (frontagehq.studio) — do not delete

## Deploy (summary)
1. Create a PUBLIC repo named  <your-username>.github.io
2. Upload every file in this folder to the repo root, commit to `main`.
3. Repo → Settings → Pages → Source: Deploy from branch → main → /(root).
4. Pages → Custom domain: frontagehq.studio → Save.
5. At your registrar, add DNS records:
   A   @   185.199.108.153
   A   @   185.199.109.153
   A   @   185.199.110.153
   A   @   185.199.111.153
   CNAME  www  <your-username>.github.io
6. Wait for DNS, then tick "Enforce HTTPS" in Pages settings.

## The contact form (already wired to Web3Forms)
1. Get a FREE access key: enter your email at https://web3forms.com
   (the key arrives by email in ~30 seconds).
2. In index.html, find:  const WEB3FORMS_KEY = "PASTE-YOUR-ACCESS-KEY-HERE";
   and paste your key between the quotes. Commit. That's it — leads
   now arrive in the inbox tied to that key.
3. OPTIONAL (auto-email the prospect for socials/photos): enable the
   Autoresponder in the Web3Forms dashboard (Pro feature) and paste
   your intake message there. Until then, reply to each lead by hand.
