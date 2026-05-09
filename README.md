# ajay-singhvi.github.io

Personal site for **Ajay Singhvi**, built with [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme. Live at **https://ajay-singhvi.github.io/**.

## Develop locally

```bash
bundle install
bundle exec jekyll serve
```

Then open the URL Jekyll prints (usually `http://127.0.0.1:4000`).

## Publish

Pushes to **`main`** run GitHub Actions: build → upload `_site` → **`deploy-pages`**. In **Settings → Pages**, **Source** should be **GitHub Actions**.

## Stanford redirect

To forward **`https://web.stanford.edu/~asinghvi/`** here, upload `stanford-www/index.html` into your Stanford **`WWW`** directory (and trim old mirrored files you no longer need).

## Optional improvements

- **Custom domain** — In Pages settings add a domain you control and put the DNS/CNAME records GitHub asks for; then set `url` in `_config.yml` to match.
- **`repository` field** — In `_config.yml`, `jekyll-github-metadata` works best if you add `repository: ajay-singhvi/ajay-singhvi.github.io` (some theme features depend on it).
- **Analytics** — Replace or remove legacy Universal Analytics in `_config.yml` if you still care about traffic stats (GA4 is the current direction).

## Theme credit

Site layout and assets derive from **al-folio** ([MIT License](https://github.com/alshedivat/al-folio/blob/master/LICENSE)). Content is mine unless noted.
