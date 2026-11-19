# Portfolio website

Static personal site: `index.html` (one page with About, Skills, Experience, Education, Outside work,
Projects, Contact), `style.css`, and project pages in `projects/` (they link back with `../style.css`).
No build step, no framework. Repo `lauvanosch-ctrl.github.io`, served by GitHub Pages at
https://lauvanosch-ctrl.github.io/. Everything in this folder is public. See `..\CLAUDE.md` for how projects connect.
Project page files use English snake_case names (e.g. `projects/portfolio_website.html`), as they appear in URLs.

## Preview
Open `index.html` with Live Server in VS Code (http://127.0.0.1:5500), or Claude checks it in the browser pane.
Check phone width (375px) as well as desktop.

## Conventions
- Page text is in English. HTML comments are in Dutch (they're Laurens's own notes); keep them.
- Placeholders still to fill in are written as `[ ... ]` in square brackets.
- Every project in the Projects section gets its own page in `projects/` with: problem, approach,
  result, screenshots, link to the GitHub repo, and what was learned.
- Keep colours and spacing in `style.css` variables; don't add inline styles.
