# OR-Action Website

This repository contains the static GitHub Pages website for **OR-Action: Multi-Role Video Understanding with Fine-Grained Actions**.

The site is a plain HTML/CSS project. GitHub Pages can publish it directly from the repository root because `index.html` is present at the top level. The `.nojekyll` file disables Jekyll processing so the files in `assets/` and `static/` are served as-is.

## Contents

- `index.html` - main project page
- `assets/` - figures, video, favicon, and paper PDF assets
- `static/css/index.css` - page styling
- `.nojekyll` - tells GitHub Pages to skip Jekyll

## Project Links

- Paper button: `assets/paper/or-action.pdf`
- Code button: <https://github.com/FelTris/or_action>
- Benchmark button: <https://github.com/FelTris/or_action/tree/main/data>

## Publishing With GitHub Pages

In the GitHub repository settings, configure:

- **Settings -> Pages**
- **Source:** Deploy from a branch
- **Branch:** `main`
- **Folder:** `/ (root)`

After saving, GitHub Pages will publish the site from `index.html`. An `index.md` file is not needed because the repository already provides `index.html` as the entry page.
