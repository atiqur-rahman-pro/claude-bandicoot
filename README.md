# 🎮 Claude Bandicoot: Shumer's Gauntlet Loop

[![Three.js](https://img.shields.io/badge/Three.js-r128-black?style=for-the-badge&logo=three.js)](https://threejs.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-Single_File_App-orange?style=for-the-badge&logo=html5)](https://developer.mozilla.org/en-US/docs/Web/HTML)

An action-packed 3D browser platformer runner inspired by *Crash Bandicoot*, built using **Three.js**, procedural 3D modeling, Web Audio API synth SFX, particle effects, and glassmorphic UI.

---

## 🔥 Features

- **Procedural 3D Character**: Custom procedural 3D Claude Bandicoot model with skeletal running, jumping, spinning, and sliding animations.
- **Action Mechanics**:
  - 🌀 **Spin Attack** (`SPACE` / `E`) — Shatters wooden crates into physics fragments!
  - 🦘 **Jump & Crate Bounce** (`W` / `↑`) — Jump over hazards or bounce off crates!
  - 🛷 **Slide** (`S` / `↓`) — Duck under high obstacles.
- **Dynamic Jungle Gauntlet**:
  - Dynamic directional sun lighting with soft shadow mapping.
  - Point torch lights and depth fog (`FogExp2`).
  - Progressive **Gauntlet Loop** difficulty scaling (speed increases with each loop!).
- **Items & Hazards**:
  - 🥭 **Wumpa Fruit** — Collect for points!
  - 📦 **Wooden Crates** — Breakable boxes with fruit bonuses.
  - 💣 **TNT & Nitro Crates** — High-hazard explosives!
  - 🛡️ **Aku Aku Mask** — Floating shield companion giving extra hit protection.
- **Pure Web Audio API**: Procedural sound synth for jumps, fruit pickups, crate breaks, and explosions (no external audio files required).
- **Zero-Build Architecture**: Entire game packaged in a single standalone HTML file.

---

## 🕹️ Controls

| Action | Keyboard | Touch / Mobile |
| :--- | :--- | :--- |
| **Move Lanes** | `A` / `D` or `←` / `→` | ◀ / ▶ Touch Buttons |
| **Jump** | `W` / `↑` | ▲ Touch Button |
| **Slide** | `S` / `↓` | ▼ Touch Button |
| **Spin Attack** | `SPACE` / `E` | 🌀 Touch Button |

---

## ⚡ Quick Start

No Node.js or build tools required! Simply clone and open `index.html` in any web browser.

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/claude-bandicoot.git

# Navigate into the folder
cd claude-bandicoot

# Open index.html directly or serve locally
python -m http.server 8080
```

Open `http://localhost:8080` in your browser and play!

---

## 🛠️ Built With

* [Three.js](https://threejs.org/) - 3D Graphics Library
* [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API) - Procedural Audio Synthesizer
* Vanilla CSS3 - Glassmorphism UI & Responsive Touch Controls

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
