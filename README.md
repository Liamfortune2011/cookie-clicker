# Ember & Crumb 🍪

A single-file idle/clicker game in the spirit of Cookie Clicker — click a cookie, hire staff and machines, buy upgrades, and watch the numbers get silly.

## Run it

No build step — it's one HTML file.

- **Locally:** just open `index.html` in a browser.
- **GitHub Pages:** push this repo, then in **Settings → Pages** set the source to the `main` branch (root). Your game will be live at `https://<your-username>.github.io/<repo-name>/`.

## How it works

- Click the cookie to bake crumbs.
- Spend crumbs on **Staff & Machines** (each gets ~15% more expensive per purchase, standard idle-game scaling).
- Spend crumbs on **Upgrades** to multiply output or click power once you own enough of a building.
- Watch for **golden crumbs** that occasionally appear on screen — click them fast for a big one-time bonus.
- Progress autosaves to your browser's `localStorage` every few seconds, plus a manual **Save** button. **Reset** wipes your save.

## Customize

Everything lives in `index.html`:

- `BUILDINGS` array — add/edit buildings, base costs, and base output.
- `UPGRADES` array — add/edit upgrades and their unlock conditions.
- CSS custom properties at the top of `<style>` — change the palette/fonts to reskin it.

Fork it, rename it, make it yours.
