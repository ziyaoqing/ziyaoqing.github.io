# Ziyao Qing — personal research website

Live site: https://ziyaoqing.github.io/

A responsive, static academic website. No framework, package installation, JavaScript build, or external hosting is required.

## Pages

| File | Purpose |
| --- | --- |
| `index.html` | Introduction, research experience, milestones and contact |
| `research.html` | Placements, interests and host-laboratory context |
| `publications.html` | Publications, presentations and planned meetings |
| `cv.html` | Curriculum vitae, with print styles |
| `404.html` | Error page with root-relative navigation and assets |
| `style.css` | Shared layout, responsive styles and print styles |
| `robots.txt`, `sitemap.xml` | Search-engine discovery |

## Publishing and recovery

GitHub repository **Settings → Pages** must use **Deploy from a branch**, branch **main**, folder **/ (root)**. A push to `main` publishes automatically. Keep `.nojekyll` in the root.

If the entire site returns GitHub’s 404, first check that the selected branch has not become **None**, then check **Actions → pages build and deployment**. A successful historical deployment does not mean Pages is still enabled. Verify the live URL after deployment, including `research.html`, `publications.html` and `cv.html`.

Preview locally with `python -m http.server 8000` and open http://localhost:8000. For a printable CV, open `cv.html` and use the browser’s Print / Save as PDF option.

## Content and image credits

Update placement dates, affiliations and milestones in both the home page and CV when they change. Keep planned attendance distinct from presentations, and host-lab funding and papers distinct from personal awards and publications. Conceptual research questions should not be presented as established findings.

The home-page micrograph is [“Microglia and neurons”](https://commons.wikimedia.org/wiki/File:Microglia_and_neurons.jpg) by GerryShaw / EnCor Biotechnology Inc., [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/). It is cropped for display. Retain its attribution. Other research figures have source and licence information beside them; preserve those credits. `brain-bone-marrow-loop.svg` is a conceptual research framework, not a quantitative result.

## October 2026 restoration

Restored Pages publishing from `main` / root; redesigned the home introduction; simplified the shared colour palette; refined mobile spacing and print pagination; clarified research questions and publication empty states; fixed nested-path 404 assets; added a sitemap and robots file.

## Scientific editorial redesign

The shared design uses Manrope headings, Source Sans 3 reading text, IBM Plex Mono annotations, charcoal and off-white surfaces, and a restrained lime accent. The homepage introduces the researcher and uses readable placement rows. Research experience precedes optional host-laboratory background; all figure credits remain adjacent to their figures. CV includes a print/save-as-PDF action and A4 print styles.

The microscope photograph is a credited reference image, not the author’s experimental data. The ZQ favicon (`images/zq-mark.svg`) is original vector artwork. Stylesheets use a content version in their URL so new HTML cannot reuse outdated styles.
