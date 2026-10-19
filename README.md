# 抓大鹅 3D POC

A mobile-first 3D take on the WeChat mini-game 抓大鹅: tap the topmost item in the basket to drop it into a 7-slot tray, three of a kind clear, empty the basket to catch the goose.

**Play:** https://talentjay-ux.github.io/zhuadae/

- Single self-contained `index.html` — three.js r128 and cannon.js 0.6.2 are inlined, no CDN, no build step, no external requests.
- Features: physics-stacked items with faces, 颠锅 (toss) button, frozen items that need a tap to crack, shuffle / magnet / remove tools, 3 levels with timers.
