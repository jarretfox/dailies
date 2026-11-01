# Dailies

Every daily puzzle game in one place. Opens a random game; **Next** gives you another; the menu lists them all.

- `index.html` is the whole site. `games.js` is the catalogue (one object per game; `embeddable: false` means the site blocks iframes and gets a new-tab card instead).
- Run locally: `dailies.bat`, or `python -m http.server 8765` in this folder.
