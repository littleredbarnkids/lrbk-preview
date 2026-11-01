# Little Red Barn Kids site v1 (STAGING DRAFT, not deployed)
Plain static HTML/CSS. Relative paths only. Works on GitHub Pages (root of repo, `.nojekyll` included) or Netlify (drag the folder in).
- `index.html` one-page site, `privacy.html`
- `assets/style.css`, `assets/fonts/` (self-hosted WOFF2 subsets, OFL), `assets/img/` (webp), `assets/video/` (30 s mp4 + .vtt captions)
- Both pages carry `<meta name="robots" content="noindex, nofollow">`. Remove it at launch.
- No CNAME yet. Add a `CNAME` file containing `littleredbarnkids.com` only after the domain is registered and J approves going live.
- Local preview: `cd site_v1 && python3 -m http.server 8765` then open http://127.0.0.1:8765/
