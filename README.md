# VirtualFit: Spatial Try-On Arc

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-brightgreen?style=flat-square)](https://shubhransh-gupta.github.io/virtualfit/)
[![Architecture](https://img.shields.io/badge/Stack-Vanilla%20HTML%20%2F%20CSS%20%2F%20JS-blue?style=flat-square)]()
[![Design](https://img.shields.io/badge/Style-visionOS%20Spatial%20Glass-purple?style=flat-square)]()

**VirtualFit** is a single-screen, visionOS-style spatial virtual try-on hero interface. It features a 3D garment arc floating in a photorealistic interior, a glowing scan-line try-on simulation on an interactive model, deep physiological body customization (height, body build, belly type, posture), photo upload, and an e-commerce product link importer for stores like Flipkart, Amazon, Snapdeal, Myntra, and Zara.

---

## 🌟 Live Demo

👉 **[https://shubhransh-gupta.github.io/virtualfit/](https://shubhransh-gupta.github.io/virtualfit/)**

---

## ✨ Key Features

### 1. 3D Spatial Garment Arc
- Frosted-glass garment cards curve around the model in a responsive 3D spatial arc with realistic perspective depth (`perspective(1300px)`), dynamic tilt (`rotateY`, `rotateX`), smooth bobbing harmonic motion, and depth blur.
- Multi-modal navigation: drag or flick with inertia, scroll wheel, arrow keys, chevron buttons, tab switches, or directly click any card.
- Dynamic sheen sweep highlight triggers seamlessly as the cursor hovers across cards.

### 2. Glowing Scan-Line Fitting Simulation
- When the arc settles on any garment, a horizontal scan line sweeps down the mannequin accompanied by a glowing scan-line grid, seamlessly revealing the model wearing that exact outfit.
- Web Animations API ensures 60 FPS transitions with zero layout thrashing (`cubic-bezier(.65,0,.35,1)`).
- On initial page load, the base mannequin remains hidden until the first scan line dramatically sweeps down to materialize him.

### 3. visionOS Spatial Glassmorphism
- Realistic frosted-glass materials (`backdrop-filter: blur(22px) saturate(1.5)`), layered inner highlights, drop shadows, and subtle ambient parallax against a blurred Scandinavian living room scene.
- Top category navigation pill bar with animated magnetic indicator (`Tops`, `Bottoms`, `Outerwear`, `Shoes`, `Accessories`).
- Floating tool rail on the left with one-click access to wardrobe hero, product link importer, fit timeline, and body customizer.
- Floating glass buy card with synchronized thumbnail bounce, rolling typography (name, price, and active color), interactive size chips (`S`, `M`, `L`, `XL`), and color palette dots.
- Interactive 58px visionOS cursor that dynamically morphs between `TRY ON`, `DRAG`, and button-focus states.

### 4. Body Customizer & Morphological Fitting Studio
Accessible via the Profile icon in the tool rail:
- **Height Calibration:** Continuous height slider (150 cm to 205 cm) with live proportional scaling.
- **Body Build Proportion:** Choose between **Slim / Flat**, **Athletic (V-Taper)**, **Regular Fit**, and **Broad / Obese**.
- **Belly & Midsection Contour:** Select from **Flat / Toned**, **Slight Curve**, **Rounded Midriff**, or **Prominent Belly**.
- **Stance & Posture:** Toggle between **Upright / Confident**, **Relaxed Neutral**, **Shoulder Drop / Slouch**, and **Forward Stance**.
- **Photo Upload:** Upload full-body or torso photos (PNG, JPG, WebP) to try on garments directly on your own photo avatar with the spatial scan line!

### 5. E-Commerce Link Try-On Importer
Accessible via the Cart icon in the tool rail:
- Paste product URLs or descriptions directly from **Flipkart**, **Amazon**, **Snapdeal**, **Myntra**, **Zara**, etc.
- 1-click trending presets for instant testing.
- Extracted garment items are instantly injected into the active 3D arc, rotating into focus with the glowing scan-line try-on effect.

### 6. Accessibility & Responsiveness
- **Mobile Optimized (≤ 767px):** Adaptive scale, horizontally scrollable pill tabs, repositioned rail, touch pan-y controls, and responsive card sizing.
- **Reduced Motion Support:** Respects `prefers-reduced-motion: reduce` by disabling non-essential bobbing, instant outfit transitions, and disabling motion sheens.

---

## 🛠️ Technology Stack

- **HTML5:** Semantic markup, responsive viewport configuration, Google Fonts preconnect.
- **CSS3:** Custom properties (CSS variables), visionOS glassmorphism, 3D CSS transforms, WebKit text strokes, media queries.
- **JavaScript (ES6+):** Pure vanilla JavaScript without external libraries or frameworks. Linear interpolation (LERP), inertia tracking, Web Animations API.

---

## 🚀 Running Locally

Simply clone the repository and open `index.html` in any modern web browser:

```bash
git clone https://github.com/shubhransh-gupta/virtualfit.git
cd virtualfit
open index.html # On macOS
```

Or run a local static server:

```bash
npx serve .
# or
python3 -m http.server 8080
```

---

## 📄 License

MIT License. Crafted with precision for the future of spatial computing and virtual fashion.
