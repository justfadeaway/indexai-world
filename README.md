# Index AI — indexai.world

Official website for **Index AI**, the data company behind frontier intelligence.

## Stack

Pure static site — a single self-contained `index.html` (no build step, no dependencies).

## Local preview

```bash
open index.html
# or serve it:
python3 -m http.server 8000
```

## Deploy

The domain `indexai.world` is already purchased. Two easy options:

### GitHub Pages
1. Push this repo to GitHub.
2. Settings → Pages → Deploy from branch (`main`, root). The included `CNAME` file maps the custom domain.
3. At your DNS provider, add an `A`/`ALIAS` record pointing `indexai.world` to GitHub Pages (`185.199.108.153` etc.) and a `CNAME` for `www`.

### Vercel / Netlify / Cloudflare Pages
Import the repo, no build command needed, output directory = root. Then add `indexai.world` as a custom domain in the dashboard.

## TODO

- Re-add the `CNAME` file (content: `indexai.world`) and the custom domain in repo Settings → Pages once DNS is configured.
