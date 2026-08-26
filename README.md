# Dala Loom

A dependency-free static company website.

## Routes

- `/` — company overview
- `/apps/` — product directory
- `/apps/qrda/` — QRda product page
- `/apps/qrda/privacy/` — QRda privacy policy

Open `index.html` directly, or run `python3 -m http.server 8080` in this directory and visit `http://localhost:8080`.

## Cloudflare Pages

This repository is ready for Cloudflare Pages' native GitHub integration. In **Workers & Pages**,
create a Pages project by importing `dalaloomstudios/dala-loom`, then use:

- Production branch: `main`
- Framework preset: `None`
- Build command: `exit 0`
- Build output directory: `.`

Cloudflare will deploy every push to `main` and create preview deployments for other branches.
