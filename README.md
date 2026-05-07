# ⚓ Yacht Rock Radio

> *Smooth sailing since 1976. A web-based audio visualizer for the sophisticated ear.*

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Stations](https://img.shields.io/badge/stations-15-gold.svg)
![Made With](https://img.shields.io/badge/made%20with-vanilla%20JS-navy.svg)

A sleek, nautical-themed internet radio player featuring **15 curated yacht rock, soft rock, and mellow grooves stations**. Built with vanilla HTML5, CSS3, and JavaScript — no frameworks, no dependencies, no nonsense. Just smooth tunes and an animated ocean sunset.

![Yacht Rock Radio Screenshot](screenshot.png)

## 🎧 Live Demo

Open `index.html` in any modern browser. That's it.

## ✨ Features

- **15 Verified Stations** — Hand-picked from 181.fm, SomaFM, and Radio Paradise
- **Real-Time Audio Visualizer** — Animated bars that react to playback state
- **Animated Ocean Sunset** — Procedural canvas waves with golden-hour gradients
- **Nautical Yacht Theme** — Brass, teak, and navy palette with porthole-style controls
- **Keyboard Accessible** — Full ARIA support and keyboard navigation
- **Mute Toggle** — Click the volume icon or press Enter/Space
- **Zero Dependencies** — Pure vanilla JS, no build step required

## 🛳️ Station Lineup

| # | Station | Genre |
|---|---------|-------|
| 1 | **181.fm Yacht Rock** | Yacht Rock |
| 2 | **SomaFM Left Coast 70s** | 70s Soft Rock |
| 3 | **181.fm Mellow Gold** | Soft Rock |
| 4 | **Radio Paradise Mellow** | Mellow Mix |
| 5 | **181.fm Super 70s** | Classic 70s |
| 6 | **181.fm Lite 80s** | Soft 80s |
| 7 | **SomaFM Illinois Lounge** | Lounge |
| 8 | **181.fm The Eagle** | Classic Rock |
| 9 | **181.fm Awesome 80s** | 80s Hits |
| 10 | **181.fm Jazz Mix** | Smooth Jazz |
| 11 | **181.fm The Breeze** | Soft Hits |
| 12 | **Radio Paradise Main** | Eclectic Rock |
| 13 | **181.fm Classic Hits** | Oldies |
| 14 | **SomaFM Lush** | Sensual Grooves |
| 15 | **181.fm Soul** | Classic Soul |

## 🚀 Quick Start

```bash
git clone https://github.com/yourusername/yacht-rock-radio.git
cd yacht-rock-radio
open index.html
```

Or simply drag `index.html` into your browser.

## 🎛️ Controls

| Control | Action |
|---------|--------|
| **Station Button** | Click to load and play a station |
| **Play / Pause** | Toggle playback |
| **Volume Slider** | Adjust volume (0-100) |
| **Volume Icon** | Click to mute / unmute |
| `Enter` / `Space` | Toggle mute when focused on volume icon |

## 🏗️ Tech Stack

- **HTML5 Audio API** — For streaming playback
- **Canvas 2D API** — For the procedural ocean animation
- **CSS3** — Gradients, backdrop filters, custom properties
- **Vanilla JavaScript** — No frameworks, no bundlers

## 🎨 Customization

### Change the color scheme
Edit the CSS custom properties in `:root`:

```css
:root {
    --navy: #0a1628;
    --teak: #8b6914;
    --brass: #d4af37;
    --cream: #f5f5dc;
}
```

### Add a station
Add an entry to the `stations` array in the `<script>`:

```javascript
{ name: "Your Station", url: "https://your-stream-url.com/stream.mp3" }
```

## 📝 License

MIT — do whatever you want, just don't sink the yacht.

---

*Made with 🥃 and smooth grooves.*
