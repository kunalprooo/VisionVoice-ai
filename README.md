# VisionVoice AI — 3D Accessibility Suite for Colorblind & Visually Impaired Users

> **Hear Colors. See the Unseen.**  
> A web-based accessibility platform built for 300M+ colorblind and visually impaired individuals worldwide.

---

## 🌟 Key Features

1. **🎨 Color Studio & Soundboard**:
   - Interactive 3D RGB Color Cube powered by Three.js.
   - Click-to-sample image pixel inspector with real-time human color names (e.g., *Vivid Teal*, *Navy Blue*).
   - 8-note Color Piano Soundboard (`A-K` keyboard controls) mapping color hues directly to musical frequencies.

2. **🧪 Ishihara Screening Test**:
   - Dark-mode 10-plate dot pattern test for Protanopia, Deuteranopia, and Tritanopia diagnosis.
   - Real-time scoring ring with detailed diagnostic summary recommendations.

3. **🔍 WCAG 2.1 Contrast Checker & Auto-Fix**:
   - Live color name text parser resolving typed color names (e.g. `red`, `navy`, `pink`, `cyan`, `gold`) into hex codes natively.
   - Instant WCAG AA / AAA compliance rating badges and one-click contrast suggestion fixes.

4. **📄 Document Reader & OCR**:
   - Printed text extraction from uploaded document photos using image processing and Web SpeechSynthesis read-aloud TTS.

5. **👁️ Vision Simulator Lenses**:
   - Real-time colorblindness simulation filters (*EnChroma*, *Protanopia*, *Deuteranopia*, *Tritanopia*, *Monochromacy*).

---

## 🚀 Quick Start

### 1. Serve Locally
```bash
python server.py
```
Open **`http://localhost:8000`** in your browser.

---

## 🛠️ Built With

- **HTML5 / CSS3 / ES6 Javascript**
- **Space Grotesk** & **Space Mono** Typography
- **Three.js** (3D RGB Color Matrix rendering)
- **Web Audio API** (Acoustic frequency synthesizer)
- **Web SpeechSynthesis API** (Voice readouts & TTS)
- **HTML5 Canvas 2D** (Pixel color sampling & Ishihara plate rendering)

---

## 📄 License
MIT License
