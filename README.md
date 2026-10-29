# Month 22 · Bubu Lotto — v1.0.0
Standalone static site for Monthsary No. 22. No build step.

## Files
- `index.html` — the monthsary page
- `support.js` — runtime the page needs (loads React from unpkg.com, so internet is required)
- `assets/stickers/` — 8 sticker images (~250 KB total)
- `404.html` — page shown for broken links
- `render.yaml` — Render config (static site, security headers, caching)
- `robots.txt` — keeps the site out of search engines

## Deploy on Render
1. Create a new GitHub repo and upload everything in this folder to the repo root.
2. On render.com: **New → Blueprint**, pick the repo, click **Apply**.
   Or **New → Static Site**, leave Build Command empty, Publish Directory `.`
3. Link: `https://bubu-lotto-m22.onrender.com` (Render adds a suffix if taken).

## Test before sharing
Scratch a ticket, print a claim stub, draw a date, pick a mood, drop a wish, drag a sticker, tap the Kulit Cam.
Saved data (scratched tickets, wishes) lives in the browser on his device only.
