# Gellért Takács — Developer Portfolio

A playful, colorful, single-page personal portfolio built with plain HTML, CSS and JavaScript.
No frameworks, no build step — it loads fast and works everywhere.

Built for the **One Who Codes 2026** portfolio challenge.

## ✨ Features
- Playful, colorful design with animated gradient blobs and a cursor-follow accent
- Fully responsive (desktop → mobile) with a mobile menu
- Accessible: semantic HTML, skip link, keyboard focus styles, alt text, and full `prefers-reduced-motion` support
- Fast: one HTML file + three optimized WebP images, lazy-loaded, no external JS libraries
- A "Surprise me" button that recolors the whole site and throws confetti 🎉

## 🗂️ Structure
```
index.html          → the whole site (HTML + CSS + JS)
assets/
  fittrack_dash.webp
  fittrack_pushup.webp
  fittrack_progress.webp
  fittrack_mobile.webp
```

## ✏️ Before you deploy — edit 4 lines
Open `index.html`, find the config block near the bottom (inside `<script>`), and fill in your links:
```js
var GITHUB_USER   = "your-github-username";
var LIVE_URL      = "#";   // your FitTrack live URL, or leave "#" to hide the button
var FITTRACK_REPO = "#";   // your FitTrack repo URL, or "#" to hide
var LINKEDIN      = "#";   // your LinkedIn URL, or "#" to hide
```
Anything left as `"#"` is hidden automatically, so there are no dead links.

## 🚀 Run locally
Just open `index.html` in a browser. (Or run any static server, e.g. `npx serve`.)

## 🛠️ Built with
HTML5 · CSS3 · vanilla JavaScript · SVG · WebP

---
Designed & built by Gellért Takács, 2026.
