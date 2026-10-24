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
| `images/avatar.jpg` | Header image (128 px) – cropped from [“Microglia and neurons”](https://commons.wikimedia.org/wiki/File:Microglia_and_neurons.jpg) by GerryShaw / EnCor Biotechnology Inc., [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/). Keep the credit line in each page footer if you keep this image. |
| `images/favicon.png` | Browser-tab icon (same image, 64 px) |

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
