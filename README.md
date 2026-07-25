# b0glarka.github.io — personal resume site

A single-page resume/portfolio site (no build step, no framework). Style modeled on the
abdullah.at layout: sticky serif nav, hero, bordered project cards, two-column skills grid.

## Files
- `index.html` — all content (edit text here)
- `styles.css` — all styling (colors, fonts, layout)
- `boga.jpg` — your headshot (any portrait crop works)

This is an overview site only; there is no resume-PDF download. Tailored CVs are generated
per job application separately.

## To preview locally
Just open `index.html` in a browser (double-click it).

## To publish at https://b0glarka.github.io
1. Create a new GitHub repo named exactly `b0glarka.github.io` (public).
2. Put `index.html`, `styles.css`, and `boga.jpg` in the repo root.
3. Push. In the repo: Settings → Pages → Source = "Deploy from a branch", Branch = `main` / root.
4. Wait ~1 minute; the site is live at https://b0glarka.github.io

## Notes
- Content is pulled from `_CVs/Petruska_Boglarka_MASTER_resume.md`. Keep the master as the
  source of truth and re-sync if you change a project or role.
- Project cards link to live demos/repos already; the Movie Recommender has no public repo so
  it intentionally has no link.
- Photo is included because a headshot is normal/expected in AT & HU. Remove the `.hero-photo`
  block in `index.html` if you ever want a text-only version.
