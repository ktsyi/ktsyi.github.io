# Personal website

Plain HTML + CSS, no build step. GitHub Pages serves it directly from the `main` branch.

```
index.html          About (bio, links, news, selected publications)
publications.html   Full publication list
cv.html             CV summary + link to PDF
style.css           All styling (colors at the top)
images/             Profile photo + publication thumbnails
papers/             PDFs (papers, cv.pdf)
```

## Common edits

- **Name / bio:** search each HTML file for "Your Name".
- **Profile photo:** add `images/profile.jpg` and change the `src` in `index.html`.
- **New paper:** copy a `<div class="pub">` block in `publications.html`.
- **Colors:** change `--accent` at the top of `style.css`.
- **Add a page:** copy `cv.html`, rename it, and add a link to the `<nav>` in every page.
