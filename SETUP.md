# Setup — one-time, ~3 minutes

This isn't a template you paste badges into. The banner is a real SVG file you own
(`assets/terminal-banner.svg`), and the snake graphic is generated fresh from your
actual GitHub contributions by a workflow that lives in your repo.

1. Create a repo on GitHub named **exactly** your username: `Aryan681/Aryan681`
   (this is the magic name GitHub uses for profile READMEs).
2. Push these three things into it:
   - `README.md`
   - `assets/terminal-banner.svg`
   - `.github/workflows/snake.yml`
3. Go to **Settings → Actions → General → Workflow permissions** and set it to
   "Read and write permissions" — the snake workflow needs this to push the
   generated SVG to an `output` branch.
4. Run the workflow once manually: **Actions tab → generate-snake → Run workflow**.
   After it finishes, `assets/snake-dark.svg` will exist and the README will pick
   it up automatically (it re-runs daily after that, no more manual steps).

That's it — no external badge services generating your main visuals, no dead
placeholder gif. The banner is static (edit the SVG directly any time you want
to change the typed lines), the snake is live.
