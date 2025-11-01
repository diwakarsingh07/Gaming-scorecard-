# Free Fire Scoreboard (Single-file)

This package contains a single-file web app (`scoreboard.html`) to run a customizable Free Fire tournament scoreboard. It works in desktop and mobile browsers and supports editing teams, auto-ranking, CSV export, background/logo upload, and PNG export.

## Files
- `scoreboard.html` — single-file web app (open in browser)
- `LICENSE` — MIT license

---

## Quick usage
1. Open `scoreboard.html` in your browser (double-click or host on a web server).
2. Click "Load Example" to populate sample teams.
3. Click cells to edit team names and numbers. Totals and Rank auto-update.
4. Upload background/logo to match your tournament branding.
5. Export PNG or download CSV to share.

---

## How to host on GitHub Pages (free)
1. Create a new GitHub repository (e.g., `freefire-scoreboard`) and push these files.
2. In the repository settings -> Pages:
   - Under "Source", choose `main` branch and `/ (root)` folder.
   - Save. GitHub will publish at `https://<your-username>.github.io/<repo-name>/scoreboard.html`
3. Wait a minute and open the URL above. Your scoreboard will be live.

Alternatively, you can use GitHub Pages with a `docs/` folder:
- Put `scoreboard.html` into `docs/` and publish Pages from `main` / `docs`.

---

## Customization ideas
- Adjust the booyah multiplier (`booyah*8`) in the HTML to match your tournament rules.
- Change colors and fonts in the `<style>` section.
- Replace header text with your event name.
