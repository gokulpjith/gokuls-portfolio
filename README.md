# 墨 / GOKUL P JITH — Manga Portfolio

A high-performance, single-file interactive portfolio website styled like a Japanese manga volume. 
Minimalist three-color palette: **Ink Black (`#0a0a0a`)**, **Paper White (`#f4f1ea`)**, and **Blood Red (`#b3001b`)**.

---

## ⚡ Quick Start

### Option 1: Direct Browser Launch
Simply double-click [`index.html`](file:///c:/gpj%2069/gokul%20new%20portfolio/index.html) to open it in any modern browser (Chrome, Edge, Firefox, Safari).

### Option 2: Local Node Dev Server
Run using Node.js:
```bash
npm start
# or
node server.js
```
Then visit [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🚀 Features & Interactive Effects

- **Katana-Slash Intro**: Diagonal cut animation that slices the screen to reveal the site with authentic manga SFX.
- **WebGL Halftone 3D Orb**: Custom Three.js shader with dynamic dot screentones, reacting to cursor movement and scroll velocity.
- **3D Manga Volume**: An interactive physical manga book with CSS 3D transforms that tracks the cursor and flips on click.
- **Focus-Line Page Transitions**: Navigating sections triggers manga speed lines and kanji page cuts (`頁`).
- **Dynamic Project Showcase**: 3D tilt card for NutriDecide that flips to explain workflow steps with stamps and badges.
- **Caution-Tape Scroll Bands**: Scroll-driven skewed text tracks reacting to scrolling physics.
- **Hand-Drawn Line-Boil Borders**: SVG turbulence filter mimicking traditional hand-inked line work.
- **Ink Splatter Cursor**: Custom blood-red reticle that splatters ink blots on click.

---

## 🛠 Project Structure

```
gokul new portfolio/
├── index.html        # Main standalone portfolio application
├── server.js         # Lightweight local dev server (zero dependencies)
├── package.json      # NPM scripts (npm start, npm run dev)
├── .gitignore        # Standard Git ignore rules
├── gokul2.md         # Original specification & notes
└── README.md         # Project documentation
```

---

## 🎨 Customization Guide

### 1. Colors
Inside [`index.html`](file:///c:/gpj%2069/gokul%20new%20portfolio/index.html) (Lines 14–18):
```css
:root {
  --ink: #0a0a0a;
  --paper: #f4f1ea;
  --blood: #b3001b;
  --wine: #6d0015;
}
```

### 2. Experience & Dates
Update the timeline card under `<section id="experience">` (Lines 511–523).

### 3. Projects & Links
- Update project links and descriptions under `<section id="projects">`.
- Add more project panels by copying the `.next` aside block or duplicating `.card3d`.

---

## 🌐 Free Deployment Options

- **GitHub Pages**:
  1. Push this folder to a GitHub repository.
  2. Go to **Settings** > **Pages** and select the `main` branch.
- **Netlify Drop**:
  - Drag and drop this folder onto [app.netlify.com/drop](https://app.netlify.com/drop).
- **Vercel**:
  - Run `npx vercel` or import the repository on [vercel.com](https://vercel.com).
