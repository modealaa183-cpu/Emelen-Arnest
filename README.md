# Emelen Arnest — Portfolio

A one-page, dark, premium portfolio website for Emelen Arnest, Senior Graphic Designer.

## What's inside
- `index.html` — the full site (HTML + CSS + JS in a single file, no build step)

## Run locally
Just open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy with GitHub Pages
1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Save — your site will be live at `https://<username>.github.io/<repo-name>/`.

## Customize
- Swap the Unsplash placeholder image URLs (hero portrait + work gallery) for real photos.
- Update the social links in the floating rail and the Contact section (LinkedIn, Behance, WhatsApp, email).
- Colors and type live as CSS custom properties at the top of the `<style>` block in `index.html` — edit `--bronze`, `--violet`, `--ink`, etc. to retheme.
