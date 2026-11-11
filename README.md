# Freddy Hany Edward — Portfolio

Personal portfolio site. Static HTML, no build step, no dependencies.

**Live:** _(add URL once deployed)_

## Structure

```
index.html     the whole site — markup, styles and script in one file
assets/        project screenshots, CV page renders, avatar, favicon
cv/            downloadable CV (PDF)
```

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

## Deploying

Any static host works — the site is plain files with no server-side code.
Connect this repository to Vercel, Netlify, Cloudflare Pages or GitHub Pages
and point it at the repository root.

## Updating the CV

Replace `cv/Freddy-Hany-Edward-CV.pdf`, then re-render the preview images
(`assets/cv-page-1.jpg`, `cv-page-2.jpg`, `cv-thumb-1.jpg`, `cv-thumb-2.jpg`)
and update the file size and date shown in the CV section of `index.html`.
