# 0xnull: Spatial Try-On & Virtual Fitting Room

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-brightgreen?style=flat-square)](https://shubhransh-gupta.github.io/virtualfit/)
[![Architecture](https://img.shields.io/badge/Stack-Vanilla%20HTML%20%2F%20CSS%20%2F%20JS-blue?style=flat-square)]()
[![Design](https://img.shields.io/badge/Style-visionOS%20Spatial%20Glass-purple?style=flat-square)]()
[![Brand](https://img.shields.io/badge/Brand-0xnull-black?style=flat-square)]()

**0xnull** is a next-generation visionOS-style spatial virtual try-on and e-commerce platform. It combines a 3D garment arc floating in a high-fidelity living space with **automatic AI facial recognition & head-swap mapping**, comprehensive body posture & contour customization, integrated storefront sales, and **live Flipkart & e-commerce product link try-ons**.

---

## 🌟 Live Demo

👉 **[https://shubhransh-gupta.github.io/virtualfit/](https://shubhransh-gupta.github.io/virtualfit/)**

---

## ✨ What's New in 0xnull

### 👤 1. AI Facial Recognition & Avatar Head-Swap
- **Intelligent Face Detection:** Uses the native browser `FaceDetector` API with an ultra-fast skin chrominance (YCbCr) centroid algorithm fallback.
- **Anatomical Grafting:** Automatically isolates the face, feather-blends edges with an elliptical gradient mask, and seats it directly atop the 3D spatial avatar.
- **Precision Alignment Studio:** Real-time controls to adjust face zoom/scale, vertical offset (nudge Y), horizontal offset (nudge X), or 1-click auto-recenter.
- **Cohesive Try-On Scan:** The glowing horizontal scan line sweeps seamlessly down through your face and across the garment during every outfit transition.

### 🛍️ 2. Flipkart & Multi-Store Link Importer
- **Paste Any Product Link:** Directly paste URLs from **Flipkart**, Amazon, Snapdeal, or Myntra.
- **1-Click Trending Flipkart Garments:**
  - *Flipkart Roadster Utility Overshirt (₹1,499)*
  - *Flipkart Highlander Heavy Denim Jacket (₹2,199)*
  - *Flipkart Metronaut Cyber Graphic Hoodie (₹1,799)*
- **Instant Spatial Arc Injection:** Extracted items are materialized as 3D frosted-glass cards in the arc with dual pricing in INR (`₹`) and USD (`$`) plus direct "Buy on Flipkart" actions.

### 💳 3. 0xnull E-Commerce Storefront & Shopping Bag
- **Our Signature Collection:** High-concept spatial garments (*0xnull Core Tee, Liquid Fleece, Minimalist Linen, Stealth Hoodie, Contrast Ringer*).
- **Interactive Shopping Bag:** Real-time cart drawer, size/color variant tracking, subtotal calculation, and instant 1-click checkout flow.

### 🥽 4. Iconic visionOS Spatial Architecture
- Frosted-glass cards in a responsive 3D spatial arc with realistic depth (`perspective(1300px)`), tilt, and harmonic bobbing.
- 58px dynamic spatial cursor (`TRY ON`, `DRAG`, button magnetism).
- Giant ghosted `0xNULL` typography with staggered rise animation.
- Physiological body customizer (Height, Slim/Flat, Athletic, Husky/Obese builds, Belly contour, and Stance).

---

## 🚀 Running Locally

```bash
git clone https://github.com/shubhransh-gupta/virtualfit.git
cd virtualfit
open index.html # On macOS
```

---

## 📄 License

MIT License. Designed and built for the future of spatial computing and fashion retail.
