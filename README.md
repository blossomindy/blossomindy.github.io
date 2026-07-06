# blossomindy.github.io

Personal portfolio site for Minkyung Lee. It's plain HTML/CSS with no build step, served via GitHub Pages.

Live: **https://blossomindy.github.io**

## Structure

```
.
├── index.html      # Page content (Bio / News / Projects / Writing)
├── style.css       # Styling (light/dark mode, responsive)
├── images/         # Profile photo and project thumbnails
│   ├── mindy.JPEG      # Profile photo
│   ├── project1.png
│   └── favicon.ico
├── .nojekyll       # Tells GitHub Pages to serve raw HTML without Jekyll
└── README.md
```

## Editing

- **Intro text**: edit the paragraph inside `<header class="bio">` in `index.html`.
- **Profile photo**: replace `images/mindy.JPEG` (keep the same filename to skip editing paths).
- **Add a project**: copy an `<article class="item">` block in `index.html`.
- **Colors / fonts / sizes**: edit the `:root` variables and rules at the top of `style.css`.

## Local preview

No build required. Open `index.html` directly in a browser, or run:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Pushing to the `main` branch triggers an automatic GitHub Pages deploy.
Configured under Settings → Pages → Source: `main` / `/ (root)`.
