# Cleopatra XI website

Modern Astro website for https://cleopatra-xi.com, hosted on Cloudflare Pages.

## Local development

```bash
npm install
npm run dev
```

## Cloudflare Pages build settings

- Framework preset: **Astro** (or None)
- Build command: `npm run build`
- Build output directory: `dist`
- Root directory: repository root (leave blank)
- Production branch: `main`

## Publishing news

Create a new Markdown file in `src/content/news/` with frontmatter:

```md
---
title: Example announcement
date: 2026-10-08
category: Announcement
summary: A short description shown on the homepage.
---

Article body goes here.
```

Commit to `main` and Cloudflare Pages will rebuild automatically. The homepage displays the 3 newest articles.

## Artwork

Place a properly licensed, high-resolution FFXI image at `public/images/hero.jpg` for the cinematic hero. The page already includes a gradient fallback, so it works before an image is added.

## Important

The launcher download and community links are intentionally placeholders until official destinations are ready. Replace these with verified URLs before launch.
