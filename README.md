# Erik Winston — Portfolio Site

Plain HTML/CSS/JS portfolio site. No build step, no dependencies.

## Preview locally

```
node serve.js
```

Then open http://localhost:5179.

## Deploy

Static files only — host anywhere that serves static assets (GitHub Pages, Netlify, Vercel, etc.).
For GitHub Pages: push this repo, then enable Pages in the repo settings (source: `main` branch, root folder).

## Structure

- `index.html`, `rocketry.html`, `projects.html`, `beyond-engineering.html` — pages
- `css/style.css` — shared stylesheet
- `js/main.js` — mobile nav toggle
- `assets/` — images, video, and resume PDF, grouped by page
