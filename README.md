# news — Big News Brief

#MadeByHasif — big-impact news only: Malaysia, Global and Geopolitics (Reuters-first).

- Live at https://news.hasifzul.com — static site hosted on Cloudflare Pages (project: `news`).
- `data/latest.json` = current edition; `data/archive.json` = last 14 daily editions.
- Data is refreshed automatically 4x daily (6am, 12pm, 6pm, 12am MYT) by a scheduled Claude task that commits new JSON to this repo. Each commit triggers a Cloudflare Pages redeploy.

Do not edit `data/*.json` by hand — the next refresh overwrites them.
