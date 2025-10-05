# Best Buys & Price Advice — Starter Site

A free, static site for price comparison and buying advice, ready for GitHub Pages.

## Quick start

1. Create a new GitHub repo and push these files.
2. In repo Settings → Pages, set Source to `Deploy from a branch` (main) and folder `/ (root)`.
3. Update `_config.yml` with your `url` and (if needed) `baseurl`.
4. Edit `_data/top_deals.yml` and the guides in `_guides/` with your picks and links.
5. Add an affiliate disclosure footer (already included) and keep it up to date.

## Writing new guides

Create a new file in `_guides/your-title.md` with front matter:

```
---
layout: post
title: Your guide title
excerpt: One-line summary
---
```

Then write Markdown content and tables. Links will be auto-monetised if you use an affiliate aggregator.

## Optional

- Custom domain: add a `CNAME` file with your domain.
- Newsletter: embed your Substack/Beehiiv form in `pages/newsletter.md`.
