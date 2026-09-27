# Old site (Olyve theme, static stub) - reviewed

This is the static-site folder from Peterorok_com.rar, made deployable:
- Pages moved to the repo root so Netlify serves index.html at /.
- Fixed the stylesheet link (it pointed at assets/css/style.css, which never existed).
- Removed two scripts that needed jQuery, which was never loaded (they only threw errors).
- Left out the WordPress PHP files and the Olyve plugin zips: they cannot run on Netlify.

What it contains: 6 pages (home, about, portfolio, blog, contact, 404) with the theme's placeholder text. No personal content.

Licence: Olyve is a ThemeForest theme under a regular licence. Keep this repo PRIVATE; do not make the theme files public.

Deploy: push to a private GitHub repo, then Netlify > Import from Git, no build command, publish directory `/`.
