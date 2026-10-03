# Michael Suarez — Portfolio

Static portfolio site (HTML/CSS/vanilla JS, no build step).

## Pages
- `index.html` — Home
- `about.html` — About Me
- `experience.html` — Experience (linked from About Me)
- `projects.html` — Projects
- `contact.html` — Contact

## Run locally
Open `index.html` in a browser, or serve the folder:

```
python -m http.server 8000
```

## Before publishing
- Add photos to `images/` (see `images/README.md`).
- In `js/main.js`, set `CONFIG.contactEmail` and optionally `CONFIG.formEndpoint` (e.g. a Formspree URL). Without an endpoint the form opens the visitor's email app.
- In `contact.html`, replace the `#` LinkedIn/GitHub links and add `resume.pdf` to the repo root.
- In `projects.html`, point the "Read more" / "View report" links at real pages or repos.

## Deploy
Works as-is on GitHub Pages (Settings → Pages → deploy from `main`), Netlify, or Vercel.
