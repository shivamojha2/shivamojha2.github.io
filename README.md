# shivamojha2.github.io

Personal website — plain HTML/CSS/JS, no build step.

## Structure

- `index.html` — page content and sections
- `css/style.css` — all styling
- `js/main.js` — mobile nav toggle + footer year
- `assets/` — headshot photo and resume PDF

## Editing

Open `index.html` in any editor and edit the text directly. To preview locally, just open `index.html` in a browser, or run:

```bash
python3 -m http.server 8000
```

and visit `http://localhost:8000`.

## Deploying

Push to a GitHub repo named `<your-username>.github.io` — GitHub Pages serves it automatically from the repo root, no configuration needed.

When you change `css/style.css`, bump the `?v=` number on its `<link>` in `index.html` — mobile browsers cache CSS aggressively, and without a version bump, phones may keep showing the old stylesheet after a deploy.
