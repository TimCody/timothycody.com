# timothycody.com

Personal portfolio of [Timothy Cody](https://timothycody.com): senior staff engineer and founder of [Built Correct](https://builtcorrect.com).

A single static page (`index.html`) plus `assets/`. No build step.

Styles live in `assets/site.css`; the mobile navigation and optional reveal animations live in `assets/site.js`. Content and section links remain available without JavaScript. The Workpapers screenshot intentionally scrolls horizontally on phones.

**Deploy:** push to `main`. The server pulls `main` every minute and nginx serves the files directly.

**Preview locally:** `python3 -m http.server 8765` in this folder, then open http://localhost:8765.
