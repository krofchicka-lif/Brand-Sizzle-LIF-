# LIF GTM Sizzle — deploy build

Static site. Publish directory: this folder.

- `index.html` — the 23-page sizzle (same source as `LIF GTM Sizzle.dc.html`)
- `support.js`, `osnet.js` — runtime + network model
- `fonts/`, `img/`, `assets/` — only the files the page actually loads

## Netlify
Drag this folder into Netlify, or connect the repo and set publish directory to `deploy` (root `netlify.toml` already does this). The hidden `lif-brand-share` form in `index.html` is there so Netlify Forms registers the fields the in-page form posts.

## GitHub Pages
Push the repo and serve from `/deploy` on your chosen branch.
