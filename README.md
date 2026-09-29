# My Supra Human
Single-file static web app: open `index.html` directly or host it anywhere (GitHub Pages, Netlify, S3...).
All data lives in the browser's localStorage (key `suprahuman.v1`). Use Settings (top-right) → Export/Import for JSON backups.

- `index.html` — the whole app (built by concatenating `src/*` in order: `cat src/0* > index.html`)
- `tools/test.js` — headless Chrome test + screenshots (`cd tools && node test.js`)
- `screenshots/` — 390x844 @3x phone screenshots (with demo data)
