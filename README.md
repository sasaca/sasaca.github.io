# santiago-saca — personal site

Personal portfolio of Santiago Saca — business data consultant & builder.

**Live:** https://sasaca.github.io

One HTML file, two typefaces, no frameworks, no build step.

- `index.html` — the entire site (markup, styles, and a small scroll-reveal script inline)
- `assets/img/` — project screenshots and photos

To update: edit `index.html`, commit, push. GitHub Pages redeploys automatically.

## Maintenance notes

- **Future steps** are tracked in [Issues](https://github.com/sasaca/sasaca.github.io/issues) — see the “Roadmap — future steps” tracking issue.
- **Demo heartbeat**: the `demo-heartbeat` Action checks the site and all four live demos hourly and emails on failure. Run history is under the Actions tab; no maintenance needed unless an email arrives.
- **Workflow files** (`.github/workflows/`) must be edited through the GitHub web UI — local git credentials lack the `workflow` scope and pushes touching them are rejected.
- **Screenshots**: if a product's UI changes significantly, retake its screenshot and replace the file in `assets/img/` (1440px wide JPEG, quality ~76).
- **OG image**: social networks cache `assets/img/og.png` near-permanently — if it's ever redesigned, rename it (e.g. `og-v2.png`) and update the meta tags rather than overwriting.
