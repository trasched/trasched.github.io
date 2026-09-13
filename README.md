# Travis Schedler personal website

A deliberately simple static website for GitHub Pages.

Files:
- `index.html` — home page
- `research.html` — research, selected papers, talks, and organisation
- `style.css` — all visual styling
- `cv.pdf` — CV linked from the site
- `.nojekyll` — tells GitHub Pages to serve the files as plain static files

## Publish

Create a repository named `<your-github-username>.github.io`, upload these files to its top level, then go to **Settings → Pages** and choose **Deploy from a branch**, branch `main`, folder `/(root)`.

The portrait is currently loaded from the Imperial profile URL. To make the site independent of Imperial's image URL later, save a portrait as `photo.jpg` in this repository and change the `src=` in `index.html` to `photo.jpg`.
