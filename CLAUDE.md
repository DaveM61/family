# family.daveandmike.net — Repo Context

See ~/Documents/Git/CLAUDE.md for the full dave&mike visual system.

## Structure
- `index.html` — family landing page (inline styles, standard header pattern)
- `assets/family_header.png` — header photo (used by all pages in this repo)
- `musel/xmas_eve_apple.html` — The Musel Family's Christmas Eve Apple
- `musel/agnes-rebik/agnes_rebik_storybook_v4.html` — Agnes Rebik storybook

## index.html
- Standard header pattern (see global CLAUDE.md)
- Uses `.header-img-zone` for the photo zone

## Content pages (musel/ and musel/agnes-rebik/)
- Use **fixed** `.dnm-header` instead of the standard static header
- Photo zone class is `.dnm-header-img-zone` (not `.header-img-zone`)
- Mobile gradient media query targets `.dnm-header-img-zone` accordingly
- `musel/` pages: image paths use `../assets/` (one level up)
- `musel/agnes-rebik/` pages: image paths use `../../assets/` (two levels up)
