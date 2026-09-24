### yashmishra.xyz ✦ Neocities Indie Web Station

My personal website — handcrafted and hosted on [Neocities](https://neocities.org). Built with pure HTML, modern Vanilla CSS, and JavaScript, celebrating the indie web and retro personal homepages.

### Live Site

[yashmishra.neocities.org](https://yashmishra.neocities.org)

---

### Core Features

- **Retro Aesthetics & CRT Engine:** Subtle CRT scanline overlay, glowing phosphor accents, and toggleable retro scanline mode (`[ 📺 CRT ]`).
- **Multi-Track Audio & Equalizer:** Custom retro music player featuring MGS3 *Snake Eater*, Celeste chiptune, and a built-in Web Audio API 8-bit synthesizer with animated frequency bars.
- **Interactive Guestbook:** Visitors can sign their handle, choose a retro pixel badge, and leave notes stored locally via `localStorage`.
- **Classic 88x31 Badges:** Hand-crafted, zero-dependency SVG pixel badges honoring Neocities, HTML5, Firefox, and the indie web.
- **Filterable Projects Matrix:** 6-project showcase with instant tag filters (`All`, `React`, `Full Stack`, `APIs`).
- **Interactive Devlog:** Categorized site changelog and engineering progress logs.
- **Easter Eggs:** Konami Code keyboard shortcut (`↑ ↑ ↓ ↓ ← → ← → B A`) activates Cyberpunk Neon Party Mode.
- **Retro CV Viewer:** In-browser resume viewer with instant print/PDF formatting.

---

### Files Structure

- `index.html` — Semantic HTML5 structure, SEO meta tags, SVG badges, and interactive JavaScript logic.
- `styles.css` — Custom CSS architecture, retro VT323 & Press Start 2P typography, CRT scanlines, and responsive grids.
- `dpp.png` — Pixel/retro profile avatar image.
- `README.md` — Project documentation and setup guide.

---

### Built With

- **HTML5 & CSS3** (Vanilla CSS Grid & Flexbox, CSS Custom Properties)
- **Vanilla JavaScript & Web Audio API** (Zero external libraries)
- [Press Start 2P](https://fonts.google.com/specimen/Press+Start+2P) — pixel font
- [VT323](https://fonts.google.com/specimen/VT323) — terminal body font

---

### Local Development

To run and preview locally:

```bash
# Using Node.js / npx
npx serve .

# Or open index.html directly in any web browser
```

---

### Neocities Deployment

1. Log in to [neocities.org](https://neocities.org).
2. Upload `index.html`, `styles.css`, and `dpp.png` directly into your Neocities root directory (or use the Neocities CLI).
