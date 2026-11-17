# Mandar Babar — Personal Archive

A single-page personal resume / work archive built with vanilla HTML and CSS.

## Files

- `index.html` — semantic page structure and content
- `styles.css` — visual system, layout, interactions and responsive rules
- `assets/images/` — selected images extracted from the user's portfolio evidence PDF
- `assets/media/` — reserved for optional video/media files

## Preview locally

Open `index.html` in a modern browser. No build step, package manager or JavaScript framework is required.

For a local development server, from this folder run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy with GitHub Pages

1. Create or open the intended GitHub repository.
2. Upload `index.html`, `styles.css`, and the complete `assets` folder to the repository root.
3. In the repository, open **Settings → Pages**.
4. Select **Deploy from a branch**, choose the main branch and `/ (root)`, then save.
5. After GitHub Pages publishes the site, open the generated URL and check it on desktop and mobile.

Do not upload only the HTML file; the styles and images must be included with the same folder structure.

## Before public deployment

- Confirm the Google Drive editing-work folder is shared with the intended audience. The link may otherwise ask visitors for access.
- Review the CTRL+GAME fan-inspired product images and keep the disclaimer in the project section. The designs should not imply endorsement or affiliation with players or clubs.
- Confirm all facts, dates, labels and images are suitable for public viewing.
- Add a professional contact method only if you choose to publish one; none was supplied, so the current page does not invent one.
- The prototype image for LawQuest currently displays an earlier interface label, “Law Drill”. The page explains this distinction.
- The running route/map screenshot was intentionally not used. The page uses the recorded 18.16 km distance and 5 km personal best without exposing the activity map.

## Design / implementation notes

- Palette: Silver Mist `#E7E8E5`, Porcelain `#F5F5F1`, Athletic Crimson `#9D3448`, Muted Forest `#587261`, Graphite `#292D2B`.
- Typography: Instrument Serif, DM Sans and IBM Plex Mono, with system fallbacks.
- Horizontal evidence galleries use CSS overflow scrolling and `scroll-snap`; no slider library is required.
- Motion is limited to short image transitions and respects `prefers-reduced-motion`.
- The implementation intentionally avoids JavaScript and external UI frameworks.
