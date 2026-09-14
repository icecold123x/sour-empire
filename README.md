# 🍋 Sour Empire

A 3D incremental tycoon that runs entirely in your browser. Start with one dollar
and a folding table on your own lawn; finish with an orbital peeling plant and a
reactor you charge once and keep forever.

**▶ [Play it here](https://icecold123x.github.io/sour-empire/)**

No install, no account, no ads, no microtransactions. Your save lives in your own
browser.

---

## What you actually do

You *walk* the world. Every business is a building on a street you stand in front
of, and every upgrade is a pad you physically step onto — it isn't a menu with a
number going up.

**Eight businesses, one street at a time**

| # | Business | What it looks like |
|---|---|---|
| 1 | The Curb Stand | a folding table on the corner of your lawn |
| 2 | ZipZest Couriers | a delivery yard with vans that leave |
| 3 | The Crate Yard | stacked, forklifted, fenced |
| 4 | The Pith Exchange | a glass trading tower |
| 5 | Rindworks Labs | a gated research campus |
| 6 | AutoGrove Robotics | an assembly line that never stops |
| 7 | Citrus Sovereignty | a marble capitol on the hill |
| 8 | OrbitPeel Industries | a spaceport apron, and something enormous on it |

**Six ways to reset for more power**

- **Rebirth** — trade the run for permanent Backers
- **Descent** — go *down* instead of up, through ten fruit stages, for raw speed
- **The Spire** — fourteen permanent steps, climbed one at a time
- **Ascension** — everything multiplies, everything costs more
- **Project Gateway** — eight modules priced in Ascensions, not cash
- **The World Reactor** — charge it once, keep the bonus forever

**And the things nobody tells you about**

- a walled orchard with its own token economy and twenty fruit mutations
- a manhole in the street, a drain beneath it, two lever puzzles down there
- weather that changes the whole world's output, including one kind that shouldn't exist
- phone deals you can haggle — push for more, risk the caller hanging up
- two minigames, nine companions, a cosmic currency you won't see for hours
- an invasion event that turns the sky a colour it has no business being

Managers keep every automated business running while you're away, for up to three
days. You come back to a breakdown of exactly who earned what.

## Controls

| Key | Does |
|---|---|
| `W A S D` / arrows | walk |
| `E` | interact with whatever you're standing on |
| `Space` | collect / the big contextual action |
| `M` | manage businesses |
| `P` | powers |
| `G` | the Grove (once unlocked) |
| `R` | resets — Rebirth, Descent, Ascension |
| `T` | travel between zones |
| `Q` / `Z` | rotate the camera |
| `Esc` | close a panel |

Mouse: drag to swing the camera, scroll to zoom. On phones and tablets there's a
thumbstick bottom-left and you swipe the right half of the screen to look around.

## Running it locally

It's a single HTML file — open `index.html` in any modern browser and it works.

For a fully offline copy, download [Three.js r128](https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js)
and save it as `vendor/three.min.js`. The game prefers that local copy and only
falls back to the CDN when it's missing.

## Requirements

Any browser with WebGL 2.0 — Chrome, Firefox, Edge, or Safari 15+. Works on
integrated graphics. No server, no build step, no dependencies to install.

## Built with

[Three.js](https://threejs.org/) r128, and nothing else. All world geometry, UI,
signage and effects are generated in code — no external models or textures.

## License

MIT — see [LICENSE](LICENSE). If you'd rather nobody reuse the code, delete that
file and replace it with "All rights reserved."
