# Putting this on GitHub Pages

Two routes. Pick one. Both end with a public link anyone can play.

---

## Route A — no command line (5 minutes)

1. Go to <https://github.com/new>.
2. Repository name: `sour-empire`. Set it **Public**. Don't tick "Add a README"
   — this folder already has one. Click **Create repository**.
3. On the empty repo page click **uploading an existing file**.
4. Drag in everything from this folder: `index.html`, `README.md`, `LICENSE`,
   `PUBLISH.md`, `.gitignore`, `.nojekyll`, and the `vendor` folder.
   *(If `.gitignore` and `.nojekyll` don't show in your file picker, turn on
   hidden files — or skip them, they're optional.)*
5. Click **Commit changes**.
6. Go to **Settings → Pages**. Under *Source* pick **Deploy from a branch**,
   branch **main**, folder **/ (root)**. Click **Save**.
7. Wait about a minute, then open:
   `https://YOUR-USERNAME.github.io/sour-empire/`

That URL is your game. Paste it into the README's Play link and into the repo's
**About** box (the gear icon, top right of the repo page) so it shows up front.

---

## Route B — command line

From inside this folder:

```bash
git init
git add .
git commit -m "Sour Empire: 3D incremental tycoon"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/sour-empire.git
git push -u origin main
```

Then do step 6 above to switch Pages on.

---

## After it's live

- **Replace `YOUR-USERNAME`** in `README.md` with your actual GitHub username, in
  both the Play link and anywhere else it appears.
- **Add screenshots.** Make a `screenshots/` folder, drop 3–4 PNGs in, and put
  `![](screenshots/street.png)` near the top of the README. A repo with a picture
  gets opened; one without gets scrolled past.
- **Set the About box** — short description, the Pages URL, and topics like
  `game`, `threejs`, `incremental`, `idle-game`, `tycoon`, `webgl`,
  `javascript`, `browser-game`. Topics are how people actually find repos.
- **Where to share it**: r/incremental_games (they're the exact audience and very
  receptive to browser games), r/WebGames, r/threejs, itch.io as a second home —
  itch is free, takes the same HTML file zipped, and has real discovery traffic.

## Updating it later

Edit `index.html`, commit, push. Pages redeploys in about a minute. Players'
saves are stored in their own browser and survive updates.
