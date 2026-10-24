# 🫧 Bubble Pop — Master Touch Typing (PWA)

An interactive, responsive Progressive Web App (PWA) designed to master touch typing from beginner to champion. Built with vanilla HTML5, CSS3, JavaScript, and Web Audio API synthesizer.

🌐 **Live Website**: [https://ainamganesh.github.io/bubble-typing/](https://ainamganesh.github.io/bubble-typing/)

---

## ✨ Features

- 🎯 **30 Sequential Learning Stages**: Starting from home row anchor keys (`F`, `J`) with physical tactile bump guidance, advancing through top row, bottom row, numbers, and symbols.
- 📝 **15 Word Rounds**: Drill real vocabulary using only keys learned up to that stage.
- 🎨 **3 Visual Themes**:
  - 🫧 **Bubbles Mode** (Stages 1–10)
  - 💎 **Gems Neon Mode** (Stages 11–20)
  - 🚀 **Cosmic Space Mode** (Stages 21–30)
- 🎵 **Synthesized Web Audio**: Dynamic calm lofi chords (Cmaj7 ➔ Am7 ➔ Fmaj7 ➔ G7sus) and realistic water bubble pop sound effects without external audio files.
- 📱 **Progressive Web App (PWA)**:
  - Installable directly to Desktop or Mobile via the **📲 Install** button.
  - Fully functional **100% Offline** powered by Service Worker caching.
- 🖥️ **Full-Screen Laptop Optimization**: Maximized play arena with dynamic viewport adaptation and `⛶ Fullscreen` toggle.
- 🎯 **True Top-Bubble Priority**: Guarantees the bubble closest to the danger line pops first when duplicate letters appear.

---

## 🚀 How to Run Locally

Simply clone the repository and open `index.html` in any web browser:

```bash
git clone https://github.com/Ainamganesh/bubble-typing.git
cd bubble-typing
# Open index.html in your browser
```

---

## 🛠️ Tech Stack

- **HTML5 & CSS3** (Glassmorphism & Flexbox layout)
- **Vanilla JavaScript** (Zero dependencies)
- **Web Audio API** (Oscillators, BiquadFilters, GainNodes)
- **Service Worker & Web App Manifest** (PWA offline support)
