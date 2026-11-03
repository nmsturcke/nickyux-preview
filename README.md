# nickyux.com

Nicky’s personal portfolio: technical architecture, project delivery, and operations.

## Local preview

This is a buildless static site. No package installation is required.

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Open http://127.0.0.1:4173. Serve the repository root so absolute asset and project links resolve correctly.

## Editing

- `index.html`: introduction, selected work, capabilities, projects, about, and contact.
- `work/*/index.html`: individual project stories.
- `static/css/portfolio.css`: shared design, responsive layouts, and reduced-motion styles.
- `static/js/portfolio.js`: progressive scroll reveals and footer year. Content and navigation work without JavaScript.
- `static/js/loading.js`: original homepage logo intro; skipped for section links and reduced motion. Tab or Escape dismisses it immediately.
- `static/cv/`: English and Spanish CVs linked from the homepage.
- `404.html`: standalone error page; configure the static host to use it for missing routes.

All fonts and imagery are served locally. Pages are plain HTML with shared CSS and JavaScript, so shared navigation/footer changes should be applied across all seven pages. Existing experimental styles and scripts are retained but are not loaded by the new portfolio.

Project copy is based on the earlier preview. Before publication, review role descriptions, project status, and CVs for currency. The design deliberately omits unverified growth and impact metrics.
