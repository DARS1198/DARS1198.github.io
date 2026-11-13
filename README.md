# Diego Adrian Ramirez Salazar — Portfolio / CV

Personal portfolio site: **https://dars1198.github.io**

Robotics & Electronics Engineer (UDEM) — control systems, industrial automation and AI.

## How it works

- A single static `index.html`. No backend, no database, no cookies, no tracking.
- Bilingual (ES / EN) with a light and dark theme.
- **All content lives in the `CONTENT` block at the top of the `<script>` in `index.html`.** Edit the text there; the layout updates automatically.
- Ctrl+P prints a clean résumé version of the page.
- The HTML also carries a static Spanish copy of the content so search engines and link previews (which do not run JavaScript) see real text. The script overwrites it on load, so the `CONTENT` block stays the source of truth; after large content edits the static copy should be regenerated.
- `CONFIG.linkedin`: paste the profile URL to show a LinkedIn row. `CONFIG.pdf.en`: add an English PDF; until then the EN button links to the Spanish one.

## Updating

Edit `index.html` (on GitHub: open the file → pencil icon → *Commit changes*). GitHub Pages republishes in about a minute.
