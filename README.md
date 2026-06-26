# Personal Portfolio — GitHub Pages Starter

A single-page portfolio site: name, contact info, résumé/LinkedIn links, coding
languages, highlighted projects, and a list of other projects.

## Files

- `index.html` — page content
- `style.css` — all styling (no build step, no dependencies besides Google Fonts)

## 1. Put it on GitHub Pages

1. Create a new repository on GitHub (e.g. `yourusername.github.io` for a
   root personal site, or any repo name for a project site).
2. Add `index.html` and `style.css` to the repo root and push them.
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**,
   pick the `main` branch and `/ (root)` folder, then save.
5. GitHub will give you a URL (usually `https://yourusername.github.io/`
   or `https://yourusername.github.io/repo-name/`) — it can take a minute
   to go live.

## 2. Customize

Everything that needs editing is plain text in `index.html`:

- **Name** — replace `Your Name` in the title block, hero, and footer.
- **Email** — replace `your.email@example.com` (appears twice).
- **Résumé** — add your own `resume.pdf` to the repo root; the button
  already links to `resume.pdf`.
- **LinkedIn / GitHub** — replace `yourusername` in those links.
- **Coding Languages** — edit the `<li class="chip">` list.
- **Highlighted Projects** — there are 3 placeholder cards; edit the
  title, summary, bullet points, and GitHub link in each `<article
  class="project-card">`. Add or remove cards as needed — the grid
  reflows automatically.
- **Other Projects** — edit the `<li>` items in the `<ul class="archive-list">`.

No build tools required — just edit and push.
