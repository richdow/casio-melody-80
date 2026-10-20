# Casio Melody-80 Web Recreation

A high-fidelity, self-contained HTML/CSS/JavaScript recreation of the 1979 Casio Melody-80 musical calculator, optimized for iPhone 15 Pro Max landscape.

## Features
- Authentic visual layout matching the original (brushed metal face, LCD with day indicators, musical staff, full button array)
- Full calculator (8-digit, algebraic logic, √, %, memory)
- Calculation history with “See Calculations” panel
- Musical notes on number keys + result playback as notes (Web Audio API square-wave piezo style)
- Built-in melodies: Tarantella Napoletana, Für Elise, ascending cadence
- Shareable state (result + history) via URL
- Local persistence

## Local Preview
Open `index.html` in any modern browser. For best experience, use Safari on iPhone in landscape, or desktop browser with mobile emulation.

## Deploy to Cloudflare Pages
1. Push this folder to a GitHub repository.
2. In Cloudflare Dashboard → Pages → Create a project → Connect to Git.
3. Build settings: Framework preset = None, Build command = (empty), Build output directory = `/`.
4. Deploy. The site is fully static.

## Notes
- Audio requires a user gesture to start (browser autoplay policy).
- Sharing uses URL-encoded state (no backend required).
- Optimized for landscape; portrait shows a rotate prompt.
