# Onusthan Mela — Wireframe

Static, non-functional wireframe for Onusthan Mela, a cultural/community events directory for Bangladesh. Built as plain HTML/CSS, linked together as a small static site.

**Live:** enable GitHub Pages on this repo (Settings → Pages → Source: `main` branch, `/ (root)`) and it'll serve from `index.html`.

## Pages

| Page | File |
|---|---|
| Home | [`index.html`](index.html) |
| Events listing | [`events.html`](events.html) |
| Event detail | [`event-detail.html`](event-detail.html) |
| Categories | [`categories.html`](categories.html) |
| About | [`about.html`](about.html) |
| Contact | [`contact.html`](contact.html) |

## Notes

- No build step, no JavaScript — layout/dropdowns/the search-results lightbox use CSS only (`:hover`, `:focus-within`, `:target`).
- Shared styles and self-hosted font subsets live in [`styles.css`](styles.css) and [`fonts/`](fonts/).
- Responsive down to phone width; grid containers that collapse are tagged `.wf-stack` / `.wf-grid-tablet2` in `styles.css`.
