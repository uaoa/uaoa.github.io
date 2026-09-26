# uaoa.github.io

Home page of Zakharii Melnyk (Захарій Мельник): https://uaoa.github.io/

- `person.json` is the single source of truth about the person (names, roles, profiles, projects). Every other site and package mirrors it.
- `node build.mjs` regenerates `index.html`, `uk/index.html`, the Markdown twins, `llms.txt` and `sitemap.xml` from it.
- Served by GitHub Pages from `main` as static files (`.nojekyll`, no build step on GitHub).
