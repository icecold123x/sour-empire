# vendor/

Put `three.min.js` (Three.js **r128**) in this folder.

Download: https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js
(right-click → Save As, name it exactly `three.min.js`)

The game loads this local copy first and only falls back to the CDN if the file
is missing. On GitHub Pages either works, but shipping the local copy means the
game keeps running if the CDN is ever blocked or goes down — and it's required
if you ever wrap this as a desktop app.
