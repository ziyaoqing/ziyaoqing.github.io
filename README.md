# Ziyao Qing – personal website

Live at **https://ziyaoqing.github.io/**

Plain static HTML/CSS site for GitHub Pages (no build step).

| File | Page |
|---|---|
| `index.html` | Home / About |
| `research.html` | Research experience |
| `publications.html` | Publications |
| `cv.html` | CV |
| `style.css` | Shared styles |
| `images/art/` | Ink illustrations (home hero, page banners, chapter openers, tiles). Generated with NovelAI from original prompts and toned to the site palette by `duotone` processing; they are artistic impressions, not experimental data. The untouched originals are on the `art-src` branch. |
| `images/microglia-glyph.svg`, `images/favicon.png` | Site mark and browser-tab icon (a drawn microglia) |

## Deploy to GitHub Pages

1. On GitHub, create a **public** repository named exactly `<your-username>.github.io`.
2. Upload all files in this folder (Add file → Upload files), or:
   ```
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
   git push -u origin main
   ```
3. Repo → Settings → Pages → Source: *Deploy from a branch*, Branch: `main` / `(root)`.
4. After ~1 minute the site is live at `https://<your-username>.github.io/`.
