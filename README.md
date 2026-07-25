# lavs-site

Marketing / landing site for **[lavs](https://github.com/snoodleboot-io/lavs)** — the lowercase acronym versioning system.

Static, vanilla HTML/CSS (no build step), hosted on **GitHub Pages**. Visual language ("Observatory") is ported from the product's own design tokens for brand continuity.

## Structure

```
index.html      # the landing page (single page)
styles.css      # Observatory theme
assets/         # images (architecture diagram, sourced from the app repo)
.nojekyll       # serve files as-is (no Jekyll processing)
```

## Local preview

No toolchain — open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Deploy

Served from the `main` branch root via GitHub Pages (Settings → Pages → Branch: `main` / root).

## Content sourcing

All copy is grounded in the app repo's `README.md`, `docs/planning/ROADMAP.md`, and
`docs/design/API_CONTRACT.md` — no invented capabilities. Update this site when those change.
