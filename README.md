# CaptionKit

Browser-based auto captions for videos: Telugu, Tenglish and 25+ languages, 22 caption templates, hook text, and burned-in video export. Runs fully in the browser, no server and no usage limits.

## Use
1. Open the site in Chrome or Edge (needs HTTPS and speech recognition support).
2. Choose a video, pick the spoken language, click **Auto-generate captions**.
3. Edit captions, pick a template, then **Export video with captions**.

## Deploy on GitHub Pages
1. Create a new repo and upload `index.html`, `README.md` and `.nojekyll`.
2. Repo **Settings > Pages > Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder = `/ (root)`.
3. Wait about a minute. Your site will be at `https://<username>.github.io/<repo>/`.

## Notes
- Speech recognition uses the browser's built-in engine, so accuracy depends on Chrome/Edge.
- Fonts load from Google Fonts, so an internet connection is needed.
