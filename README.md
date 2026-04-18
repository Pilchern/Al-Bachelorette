# Casa Al-Mor

Al's bachelorette weekend villa companion — Milwaukee, June 12–14, 2026.

## What's in here

- `index.html` — the entire app (single file, no build step)
- `yt1s_jBQzYkG.mp3` — the villa soundtrack
- `.nojekyll` — tells GitHub Pages to skip Jekyll processing

## Deploy to GitHub Pages

1. Create a new public repo on GitHub (e.g. `casa-al-mor`).
2. Upload every file in this folder to the repo root (drag-and-drop works on github.com).
3. In the repo, go to **Settings → Pages**.
4. Under **Source**, pick **Deploy from a branch**.
5. Pick `main` branch, `/ (root)` folder. Save.
6. Wait about a minute. Your site will be live at:

   `https://<your-username>.github.io/casa-al-mor/`

7. Share that URL with the islanders.

## Updating later

Edit `index.html` locally, commit and push. GitHub Pages re-deploys automatically in ~1 minute.

## Local preview

Open `index.html` directly in a browser, or run a tiny server:

```
cd casa-al-mor-gh-pages
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.
