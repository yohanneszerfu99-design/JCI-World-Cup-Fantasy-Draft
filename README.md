# 🏆 World Cup 2026 Fantasy Draft Wheel

An interactive dual spin wheel app for running a FIFA World Cup 2026 fantasy draft. Spin both wheels simultaneously to randomly pair players with teams.

![Fantasy Draft](https://img.shields.io/badge/FIFA-World%20Cup%202026-gold)
![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-blue)

## Features

- **Dual Spin Wheels** — Team wheel (48 qualified nations) and Player wheel side by side
- **Fantasy Draft Pairing** — One spin picks a team AND a player, pairing them together
- **Auto-Elimination** — Selected teams and players are removed from their wheels after each pick
- **Draft Results Sidebar** — Live-updating list of all pairings with pick order
- **CSV Download** — Export your complete draft results to a CSV file
- **Confetti Celebration** — Colorful confetti on every pick
- **Responsive Layout** — Works on desktop, tablet, and mobile
- **Confederation Color Coding** — Teams colored by UEFA, CONMEBOL, CONCACAF, CAF, AFC, OFC

## How to Use

1. **Add Players** — Type names into the input field and click ADD (or press Enter)
2. **Spin Both** — Hit the SPIN BOTH button to spin both wheels simultaneously
3. **View Pairing** — The selected team and player are paired and shown in the center
4. **Repeat** — Keep spinning until all players or teams are drafted
5. **Download** — Click the ⬇ Download button to export results as CSV
6. **Reset** — Start over anytime with the RESET button

## Hosting on GitHub Pages

1. Create a new repository on GitHub
2. Push the contents of this folder to the `main` branch
3. Go to **Settings → Pages**
4. Set source to **Deploy from a branch** → `main` → `/ (root)`
5. Your site will be live at `https://<username>.github.io/<repo-name>/`

## Quick Deploy via Upload

1. Create a new repository on GitHub
2. Click **Add file → Upload files**
3. Drag and drop `index.html` and `README.md`
4. Commit to `main`
5. Enable GitHub Pages in Settings

## Tech Stack

- Pure HTML, CSS, and vanilla JavaScript
- No frameworks or dependencies
- Canvas API for wheel rendering
- Web Animations API for effects
- Single self-contained `index.html` file (including embedded assets)

## License

MIT — free to use, modify, and distribute.
