# Sebastian Munera — Portfolio

Personal portfolio site for Sebastian Munera, Financial Analyst (Vancouver, BC).

**Live:** https://sebastianmunera.mycraftconcepts.com/

## Structure

Static site, no build step. Served directly by GitHub Pages from `main`.

| Path | Purpose |
| --- | --- |
| `index.html` | The full page (markup + inline styles + page logic) |
| `support.js` | Runtime that renders the page's custom elements |
| `assets/` | Portrait and Open Graph preview image |
| `fonts/` | Inter / Inter Display webfonts |
| `resume-sebastian-munera.pdf` | Resume, linked from the hero "Resume" button |
| `CNAME` | Custom domain for GitHub Pages (`sebastianmunera.mycraftconcepts.com`) |
| `.nojekyll` | Tells Pages to serve files as-is, without Jekyll processing |

## Updating

- **Resume:** replace `resume-sebastian-munera.pdf`, keeping the same filename.
- **Page content:** edit `index.html`.

Commit to `main` and Pages redeploys automatically.

## Hosting

- **Repository:** `mycraftconcepts/sebastianmunera`, hosted by Craft Concepts Digital.
- **Domain:** `sebastianmunera.mycraftconcepts.com`, a Cloudflare CNAME record pointing to `mycraftconcepts.github.io` (DNS only, not proxied). The `mycraftconcepts.com` domain is verified in the `mycraftconcepts` GitHub organization.
- **HTTPS:** enforced in the repository's Pages settings.
- **Don't delete `CNAME`.** If the repository is ever transferred, GitHub drops the custom domain: set it again in Settings → Pages right away.
- The old address, `sebastian-munera.github.io`, no longer works.

## Local preview

```
python3 -m http.server 8000
```

Then open http://localhost:8000
