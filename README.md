# Kollin's Site

There are many websites, but this one is mine.

Small landing page for me. Read about me, my work, and other stuff.

Static site generated using the
[Hugo static site generator](https://github.com/gohugoio/hugo).

---

See [USER_GUIDE.md](./USER_GUIDE.md) for day-to-day instructions on creating, updating, and deleting content.

## Quick start

```sh
# Live preview at http://localhost:1313, includes drafts
hugo server -D

# Production build into ./public
hugo --gc --minify
```

## Repo layout

- `config/_default/` — site configuration (split by concern)
- `content/` — all page content
  - `_index.md` — homepage intro text
  - `about.md`, `services.md` — standalone pages
  - `writings/` — blog posts
  - `projects/` — case studies
- `archetypes/` — templates used by `hugo new`
- `layouts/_partials/functions/warnings.html` — **compatibility shim, do not delete**
- `themes/congo/` — theme, pulled in as a git submodule
