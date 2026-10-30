# just let me know.

Homepage for **justletmeknow.app**.

A single static page: plain HTML and CSS, no build step. Open `public/index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000 -d public
```

Deploy (Cloudflare Workers static assets, custom domains `justletmeknow.app` + `www`):

```bash
wrangler deploy
```

Typeface: Plus Jakarta Sans (loaded from Google Fonts).
