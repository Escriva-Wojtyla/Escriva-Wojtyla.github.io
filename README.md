# Portfolio

Static one-page portfolio. No build step. Hosted free on GitHub Pages.

## Files
- `index.html`: the whole site (HTML + CSS in one file)
- `photo.jpg`: hero photo

## Publish (free, GitHub Pages)
1. On GitHub, create a **public** repo named exactly `Escriva-Wojtyla.github.io`.
2. Put `index.html` and `photo.jpg` in the root of the repo and push to `main`.
3. Repo → Settings → Pages → Source: "Deploy from a branch" → `main` / `/ (root)` → Save.
4. After about a minute the site is live at https://escriva-wojtyla.github.io

From a terminal:

```bash
cd portfolio
git init -b main
git add .
git commit -m "Initial portfolio"
git remote add origin git@github.com:Escriva-Wojtyla/Escriva-Wojtyla.github.io.git
git push -u origin main
```

## Before you push: search for `EDIT`
`index.html` has `EDIT` comments marking text only you can fix (the ask, the smart home details, the repo links).
