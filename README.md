# Naloxone Advocates — Clean Static Site

This package contains a clean static website ready for GitHub → Cloudflare Pages (no headers file).

- index.html, training.html, about.html, resources.html, news.html, contact.html
- styles.css at repo root
- assets/img (logo.svg, hero.jpg)
- assets/docs (placeholder PDFs)
- 404.html and test.html included

Deploy steps:
1) Upload these files to your GitHub repo root (not inside a subfolder).
2) Cloudflare Pages project: Framework preset None, Build command blank, Output dir `/`, Root dir blank.
3) Visit your site: /, /test.html, /training.html.
