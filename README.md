# Cleopatra XI — Cinematic Website v2

Astro website for Cloudflare Pages. Responsive cinematic homepage based on the approved second mockup.

## Deploy

Upload **the contents** of this folder to the root of `Tummie-FFXI/cleopatra-website`, replacing matching files. Remove the old root `index.html` if it exists.

Cloudflare Pages settings: Build command `npm run build`, output directory `dist`, production branch `main`.

## Artwork

`public/images/hero.webp` is a scenic crop of the approved concept mockup, not a real FFXI screenshot. It can later be replaced with licensed/owned gameplay photography or a dedicated hero illustration.

## Server status

The status panel intentionally displays no fabricated player counts or uptime. Connect it to an API later.

## News

Edit Markdown files in `src/content/news/`. Required frontmatter fields: `title`, `date`, and `summary`; optional `category`.
