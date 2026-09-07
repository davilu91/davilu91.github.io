# Personal homepage

Static single-page site (`index.html`), no build step.

## Deploy to GitHub Pages
1. Create a public repo named `<username>.github.io` (user site) - or any repo and enable Pages on the `main` branch root.
2. `git init && git add . && git commit -m "homepage" && git branch -M main`
3. `git remote add origin git@github.com:<username>/<username>.github.io.git && git push -u origin main`
4. Settings → Pages → Source: Deploy from branch `main` / root. Site appears at `https://<username>.github.io` within ~1 minute.

Edit `index.html` directly; replace `REPLACE_ME` LinkedIn placeholder.
