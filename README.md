# Blockli Pages Site

Simple GitHub Pages site with a small JSON API.

Files:

- `index.html` — root page that fetches `api/token.json`.
- `api/token.json` — contains the token used for examples.

To publish:

1. Create a GitHub repo (e.g. `blockli-pages`).
2. Push this folder as the repository root or copy files into your repo root.
3. On GitHub, enable Pages from `main`/`master` branch (or `gh-pages`) in repository settings.

Optional: use the GitHub CLI to create and push:

```bash
cd "github-pages-site"
git init
git branch -M main
git add .
git commit -m "Initial Pages site"
# then either create remote on GitHub and push, or use `gh repo create`
```
