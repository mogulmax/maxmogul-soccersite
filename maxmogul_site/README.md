# Max Mogul — Static Soccer Portfolio

A clean, single‑page site you can deploy on **GitHub Pages**.

## Customize

- Replace placeholder text in `index.html`:
  - YouTube video ID (`VIDEO_ID_HERE`)
  - Contact info (email/phone/handles)
  - Stats and bio dashes
- Swap images in `assets/`:
  - `profile.jpg` — hero photo
  - `og-image.jpg` — Open Graph share image (1200×630)
  - `favicon.svg` — tab icon
  - `Max-Mogul-Resume.pdf` — your resume
- (Optional) Update social links and JSON‑LD in `<head>`.

## Deploy on GitHub Pages

1. Create a new repository named **<your‑github‑username>.github.io**.
2. Add these files to the repo root (not in a subfolder).
3. Commit & push. After a minute or two, your site will be live at:
   `https://<your‑github‑username>.github.io/`

### Alternative (project site)
- Any repo name works. In GitHub:
  - Settings → Pages → Branch: `main` → `/root`
  - Your site will be served at `https://<user>.github.io/<repo>/`
  - If using a project site, update the `og:url` and asset paths accordingly.

## Contact form (Formspree)
- Create a form at https://formspree.io/ and replace the `action` URL in the `<form>` tag.
- Or remove the form and keep only your `mailto:` link.

## Local preview
Open `index.html` in your browser (double‑click). No build or server required.

## License
Do whatever you want with it. No attribution needed.
