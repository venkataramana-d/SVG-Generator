# Edstellar SVG Studio

A browser-based SVG skill card generator for Edstellar. Generates professional skill cards and Instagram-ready graphics with customizable colors, icons, patterns, and animations — no build step required.

## Features

- **Card mode** — Generate individual skill cards with title, subtitle, description, and skill tags
- **Instagram carousel mode** — Create multi-slide carousel graphics ready for social media
- **Multiple canvas sizes** — Standard card, square, portrait, and landscape formats
- **Color palettes** — Built-in branded palettes plus full custom color support
- **Icon sets** — Curated icon library with category filtering
- **Animated SVG export** — Download SVGs with CSS animations intact
- **PNG download** — Rasterize cards to PNG via HTML5 Canvas
- **JSZip batch export** — Download multiple cards as a single ZIP archive

## Usage

1. Clone or download this repository
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari)
3. Fill in the sidebar fields and click **Generate SVG**
4. Use the export buttons to download your card(s)

No server, no build tool, no dependencies to install.

## Project Structure

```
SVG Gen/
├── index.html          # Main app entry point
├── src/
│   ├── fonts.css       # Embedded @font-face declarations (base64 woff2)
│   ├── style.css       # Application styles
│   ├── jszip.min.js    # JSZip 3.10.1 (offline bundle)
│   └── app.js          # Main application logic
└── edstellar-svg-generator_v6.1.html  # Original monolithic file (reference)
```

## Tech Stack

- **Vanilla JavaScript** — no frameworks or build tools
- **SVG** — all card graphics are pure SVG with optional CSS animations
- **HTML5 Canvas** — used for PNG rasterization
- **JSZip** — client-side ZIP file creation for batch downloads

## License

MIT
