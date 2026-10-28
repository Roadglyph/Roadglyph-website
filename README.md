# Roadglyph static site

Plain HTML/CSS. No build step.

## Before publishing
1. Put your banner image at `images/glyphs-wide.jpg` (the one used on Weebly).
2. Contact form: create a free form at https://formspree.io, then replace `YOUR_FORM_ID` in `contact.html` with your form ID.
3. Colours and fonts: edit the variables at the top of `css/style.css`.

## GitHub Pages
1. Commit everything to the repo root and push.
2. Repo **Settings → Pages → Build and deployment**: Source "Deploy from a branch", branch `main`, folder `/ (root)`.
3. After a minute the site is live at `https://<user>.github.io/<repo>/`.
4. Custom domain: add `www.roadglyph.com` under Pages → Custom domain, and point a CNAME record for `www` to `<user>.github.io` at your DNS provider.

## Moving later
Any static host works as-is: DigitalOcean App Platform (static site), Netlify, Cloudflare Pages.
