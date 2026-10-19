# Scott O'Brien — Personal Site

Single-page static site. Edit `index.html` in place — everything (markup, styles, script) is in one file for easy editing.

## Run locally

```bash
cd /Users/stevebot/projects/scott-site
python3 -m http.server 8765
# open http://localhost:8765
```

## Sections

- **About** — hero + "What I do" + tech stack
- **Experience** — vertical timeline (5 entries)
- **Contact** — "Let's work together" + email/social CTAs

Nav links smooth-scroll to each section and the active pill updates as you scroll.

## What to fill in / change

1. **Hero copy** — `<h1>` and `.lede` paragraph under About
2. **What I do** — the paragraph under the "What I do" heading
3. **Tech stack** — the `.tech-grid` divs. Swap icons (Simple Icons CDN) or add/remove cards
4. **Experience** — `.timeline-item` blocks. Copy/paste a new `<div class="timeline-item">` to add an entry. Set `muted` class for less-prominent entries
5. **Contact email** — search for `scott.thomas.obrien@gmail.com` and replace
6. **GitHub / LinkedIn** — search for `github.com/scottobrien` and `linkedin.com/in/scott-o-brien`

## Notes

- Tech icons are loaded from `cdn.jsdelivr.net/npm/simple-icons@...` — remove a card if the icon doesn't exist for your stack
- All fonts are from Google Fonts (Bricolage Grotesque + Inter)
- No build step, no dependencies. Just edit and refresh.
