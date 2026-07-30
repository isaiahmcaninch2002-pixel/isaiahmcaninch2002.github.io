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

## The contact form
GitHub Pages is static and cannot send email. Connect a free form
service (Web3Forms or Formspree) and paste its URL into the
FORM_ENDPOINT constant near the bottom of index.html.
