# Sebastian Munera — Portfolio

Personal portfolio site for Sebastian Munera, Financial Analyst (Vancouver, BC).

**Live:** https://sebastian-munera.github.io/

## Structure

Static site, no build step. Served directly by GitHub Pages from `main`.

| Path | Purpose |
| --- | --- |
| `index.html` | The full page (markup + inline styles + page logic) |
| `support.js` | Runtime that renders the page's custom elements |
| `assets/` | Portrait and Open Graph preview image |
| `fonts/` | Inter / Inter Display webfonts |
| `resume-sebastian-munera.pdf` | Resume, linked from the hero "Resume" button |
| `.nojekyll` | Tells Pages to serve files as-is, without Jekyll processing |

## Updating

- **Resume:** replace `resume-sebastian-munera.pdf`, keeping the same filename.
- **Page content:** edit `index.html`.

Commit to `main` and Pages redeploys automatically.

## Local preview

```
python3 -m http.server 8000
```

Then open http://localhost:8000
