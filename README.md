# Stash

A simple public host for images, videos, and static webpages, published with GitHub Pages.

- Site: <https://hamrick.github.io/Stash/>
- Existing video: <https://hamrick.github.io/Stash/LimitlessHeroVidNoBG.webm>

## Add content

Use these paths to keep things organized:

- `images/` for PNG, JPEG, WebP, SVG, and GIF files
- `videos/` for WebM and MP4 files
- `pages/<name>/index.html` for standalone webpages

For example, `images/example.png` will be available at:

```text
https://hamrick.github.io/Stash/images/example.png
```

A page at `pages/demo/index.html` will be available at:

```text
https://hamrick.github.io/Stash/pages/demo/
```

Use lowercase filenames without spaces for dependable URLs. This repository is public, so do not store private files, credentials, or secrets here.

GitHub Pages works well for modest static assets and simple pages. For large videos or heavy traffic, use object storage with a CDN.
