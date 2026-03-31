# 🎂 Happy Birthday Kiara — Interactive Birthday Experience

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)

*A single-file, cinematic, fully-immersive birthday website built with pure HTML, CSS & JavaScript.*

</div>

---

## ✨ Overview

This project is a **luxury, interactive birthday experience** crafted for **Kiara** — featuring stunning 3D animations, a horizontal memory timeline, interactive envelopes with personal messages, a candle-blowing mini-game, and much more. All functionality is self-contained within a **single `index.html` file**.

---

## 🚀 Features

| Feature | Description |
|---|---|
| 🎬 **Tap to Begin Curtain** | Cinematic preloader overlay before the experience starts |
| 🎂 **3D Rotating Cake** | CSS-powered animated hero cake with glowing flame & floating animation |
| ✨ **Bokeh Particle Field** | Three.js WebGL canvas rendering soft, drifting light particles |
| 📸 **Memory Timeline** | Horizontal scroll-snapping polaroid-style photo cards with flip-in animation |
| 🖼️ **GIF / Photo Wall** | Masonry grid of animated GIFs and personal photos |
| 🔮 **Orbiting Photo Sphere** | Three.js 3D sphere with orbiting photo textures |
| 💌 **Interactive Envelopes** | Click to open envelopes and reveal handwritten personal messages |
| 🕯️ **Candle Blowing Game** | Web Audio API microphone detection — blow to extinguish the candles! |
| 🎊 **Confetti Burst** | canvas-confetti celebration after all candles are blown out |
| 🎵 **Music Toggle** | Background music player with play/pause button |
| 📱 **Fully Responsive** | Adapts gracefully from mobile to widescreen |
| 🖱️ **Custom Cursor** | Gold glowing cursor replaces the default browser cursor |
| 📜 **Scroll Progress Bar** | Thin gold bar at the top tracks reading progress |
| 🌾 **Falling Petals** | Ambient animated petals drifting across the screen |

---

## 🗂️ Project Structure

```
birthday-animations/
├── index.html          # 🎯 Everything — HTML, CSS & JS in one file
├── img1.jpg         # Personal photos used in Memory Timeline & Sphere
├── img2-3.jpeg
├── img2-4.jpg
├── img2-5.jpeg
├── img2-6.jpg
├── img2-7.jpg
├── img2-8.jpg
├── img2-10.jpg
├── img2.jpg
├── img9.jpg
└── README.md           # 📄 This file
```

---

## 🎨 Design System

| Token | Value | Usage |
|---|---|---|
| `--clr-bg` | `#0a0a1a` | Deep navy/black background |
| `--clr-gold` | `#f0c060` | Primary accent — headings, cursor, borders |
| `--clr-rose` | `#e8a0bf` | Secondary accent — section titles, cake |
| `--clr-cream` | `#fdf6ec` | Body text & light surfaces |
| **Display Font** | Playfair Display | Headings & hero text |
| **Script Font** | Dancing Script | Letter/envelope messages |
| **Body Font** | DM Sans | General copy & labels |

---

## 🛠️ Tech Stack

| Library | Version | Purpose |
|---|---|---|
| [Three.js](https://threejs.org/) | r128 | Bokeh particle field & orbiting photo sphere |
| [canvas-confetti](https://github.com/catdad/canvas-confetti) | 1.6.0 | Confetti burst on candle game win |
| [Google Fonts](https://fonts.google.com/) | — | Playfair Display, Dancing Script, DM Sans |
| **Web Audio API** | Native | Microphone input for candle-blowing game |
| **Vanilla JS** | ES6+ | All interactivity — no frameworks needed |

---

## 🏃 Running Locally

No build tool or server is required. Simply open the file in any modern browser:

```bash
# Option 1 — Double-click the file in File Explorer
birthday-animations/index.html

# Option 2 — Using VS Code Live Server extension
# Right-click index.html → "Open with Live Server"

# Option 3 — Using Python's built-in server
cd birthday-animations
python -m http.server 5500
# Then open http://localhost:5500 in your browser
```

> **Note:** The **Candle Blowing Game** requires microphone access. Your browser will prompt for permission when you start the game. Allow it to use the mic-detection feature.

---

## 🧩 Sections Breakdown

```
[Curtain Overlay]  →  Tap anywhere to begin
       ↓
[Hero]             →  3D rotating cake, gradient title, bokeh particles
       ↓
[Memory Timeline]  →  Horizontal polaroid scroll with real photos
       ↓
[GIF / Photo Wall] →  Masonry grid of GIFs & friend photos
       ↓
[Photo Sphere]     →  Three.js rotating 3D sphere with orbiting images
       ↓
[Envelopes]        →  5 clickable envelopes with personal messages
       ↓
[Candle Game]      →  Blow your mic to extinguish candles & win confetti!
       ↓
[Footer]           →  Social share buttons & closing message
```

---

## 📱 Browser Compatibility

| Browser | Support |
|---|---|
| Chrome 88+ | ✅ Full |
| Firefox 85+ | ✅ Full |
| Safari 14+ | ✅ Full |
| Edge 88+ | ✅ Full |
| Mobile (iOS/Android) | ✅ Responsive |

> For the best experience, use **Google Chrome** on desktop — the Web Audio API mic feature works most reliably there.

---

## 🎁 Customisation Guide

Want to personalise this for someone else? Here are the key spots to edit inside `index.html`:

- **Name** → Search for `Kiara` and replace with your recipient's name
- **Photos** → Swap the image files and update `src` paths in the Memory Timeline and GIF Wall sections
- **Envelope Messages** → Find the `data-letter` attributes on each `.envelope-wrapper` and update the text
- **Color Palette** → Edit the `:root` CSS variables at the top of `<style>`
- **Background Music** → Add an `<audio>` `src` pointing to your chosen `.mp3` file

---

## 🙏 Credits

Built with 💛 as a personal birthday gift.

- **Three.js** — 3D rendering engine
- **canvas-confetti** — Celebration effects
- **Google Fonts** — Beautiful typography
- **Web Audio API** — Microphone-powered candle game

---

<div align="center">

*Made with love, code, and a little bit of magic ✨*

</div>
