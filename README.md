# Academic homepage

Plain HTML and CSS. No JavaScript, no build step, no dependencies.

## Files

- `index.html`: all of your content. Comments inside explain how to copy and edit each section.
- `style.css`: the look. Colors and fonts are variables at the top.
- `assets/`: your photo (`photo.jpg`), CV (`cv.pdf`), slides, etc.

## Add your photo

1. Save your picture as `assets/photo.jpg` (square-ish, at least 400×400 px).
2. In `index.html`, change `assets/photo.svg` to `assets/photo.jpg` and update the `alt` text.

## Everyday updates

Open `index.html`, copy an existing entry (a paper, a news line), paste it, edit the text. Commit. Done.
Remember to bump the "Last updated" line in the footer by hand.

## Publish on GitHub Pages

1. Create a repo named `<your-github-username>.github.io`.
2. Upload these files to the repo root.
3. Settings → Pages → Deploy from a branch → `main` → `/ (root)`.
4. The site is live at `https://<username>.github.io` in about a minute.

## Preview locally

Double-click `index.html`.
