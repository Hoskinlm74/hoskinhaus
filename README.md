# Hoskin Haus Tree Service — Static Website

This repository contains the static website for Hoskin Haus Tree Service.
Place any static assets under the `images/` folder. The site entrypoint is `Index.html`.

How to serve locally:
- Open `Index.html` in a browser, or use a simple local server:
  - Python 3: `python -m http.server 8000`
  - Node (http-server): `npx http-server .`

Deploy:
- This site is ready to deploy to Cloudflare Pages. Use branch `main` (or whichever you configure in Pages) and set the Publish directory to the repository root (`/`) with no build command.
