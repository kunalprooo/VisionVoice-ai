# VisionVoice AI — 3D Accessibility Suite for Colorblind & Visually Impaired Users

> **Hear Colors. See the Unseen.**  
> A web-based 3D accessibility platform built for 300M+ colorblind and visually impaired individuals worldwide.
> **GitHub Repository**: [github.com/googetaa/VisionVoice-ai](https://github.com/googetaa/VisionVoice-ai)

---

## 🌟 Key Features & Innovations

1. **🎨 75+ High-Precision Shade Color Classifier**:
   - Uses weighted human perceptual Euclidean distance matching ($R \times 30\%, G \times 59\%, B \times 11\%$) to accurately name any shade on Earth (*Deep Navy Blue*, *Vivid Emerald Green*, *Crimson Red*, *Turquoise Blue*, *Burnt Sienna*, *Chartreuse*, *Vivid Amber*, *Soft Lavender*, *Maroon*, *Ivory*, *Beige*, *Gold*, *Khaki*, *Mint Green*, *Seafoam*, *Aquamarine*, *Sky Blue*, *Royal Blue*, *Midnight Blue*, *Plum*, *Mauve*, *Hot Pink*, *Fuchsia*, etc.).

2. **🎹 8-Note Color Piano Soundboard (Audio Synesthesia)**:
   - Maps color spectrum hues (`Red`, `Orange`, `Yellow`, `Green`, `Cyan`, `Blue`, `Purple`, `Pink`) directly to musical pitch frequencies (`C4` 261.63Hz to `C5` 523.25Hz).
   - Allows visually impaired users to play and hear color relationships in real time using keyboard keys `A, S, D, F, G, H, J, K`.

3. **🖼️ Image Color Sampler & Palette Extractor**:
   - Upload any photo or UI mockup to extract a 5-color dominant colorblind-safe design palette.
   - Click-to-sample pixel inspector with live voice readouts and pitch frequencies.

4. **🧪 Dark-Mode Ishihara Screening Test**:
   - Interactive 10-plate dot pattern test featuring dark obsidian circles (`#0e1726`) for Protanopia, Deuteranopia, and Tritanopia diagnosis.
   - Real-time scoring ring with detailed diagnostic summary recommendations.

5. **🔍 WCAG 2.1 Contrast Checker & Auto-Fix**:
   - Live color name text parser resolving typed color names (e.g. `red`, `navy`, `pink`, `cyan`, `gold`) into hex codes natively.
   - Instant WCAG AA / AAA compliance rating badges and one-click contrast suggestion fixes.

6. **📄 Document Reader & OCR**:
   - Printed text extraction from uploaded document photos using image processing and Web SpeechSynthesis read-aloud TTS.

7. **👁️ Vision Simulator Lenses**:
   - Real-time colorblindness simulation filters (*EnChroma*, *Protanopia*, *Deuteranopia*, *Tritanopia*, *Monochromacy*).

---

## 🛠️ Production Tools & Tech Stack (8 Core Engines)

1. **Three.js Graphics Engine** — WebGL 3D RGB Color Cube matrix rendering.
2. **Web Audio API Synthesizer** — Real-time 220Hz-820Hz sine-wave frequency sound generator.
3. **Web SpeechSynthesis API** — Native voice readouts and document text-to-speech.
4. **HTML5 Canvas 2D Engine** — Pixel color sampling, palette extraction & Ishihara plate generator.
5. **Space Grotesk & Obsidian Teal Design System** — High-contrast WCAG-compliant glassmorphism UI.
6. **HTML5 Web Storage API** — LocalStorage preference persistence.
7. **Python HTTP Micro-Server** — Lightweight production server hosting (`server.py`).
8. **Git & GitHub CI/CD Pipeline** — Version control & GitHub Pages deployment.

---

## 📊 Presentation Deck

Full 8-Slide Pitch Deck with 30-Second Speaker Scripts available in [`visionvoice_pitch_deck.md`](./visionvoice_pitch_deck.md).

---

## 🚀 Quick Start

### Serve Locally
```bash
python server.py
```
Open **`http://localhost:8000`** in your browser.

---

## 📄 License
MIT License
