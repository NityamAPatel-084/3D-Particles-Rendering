# AETHER — 3D Gesture-Controlled Particle Engine

A real-time 3D particle visualization engine controlled entirely through hand gestures using MediaPipe and Three.js.

## ✨ Features

- 🖐️ **12 unique gestures** — Single-hand orbit, zoom, roll + Two-hand scale, steer, pan, explode, clap reset, freeze, precision orbit, zoom+rotate, shape cycling
- 🌌 **12 particle presets** — Lunar Galaxy, Radiant Waves, Saturn Rings, Glowing Heart, Crystal DNA, Diamond Knot, Cosmic Burst, Cube Matrix, Moon Vortex, Sparkle Wings, Quantum Nebula, Hyper-Tunnel
- 🎵 **Built-in music player** — Cyberpunk-styled with hoverable volume control
- ⚡ **Up to 36,000 particles** — Smooth morphing transitions with dynamic color spectrum shifts
- 🎮 **Mouse fallback** — Click-drag orbit + scroll zoom with auto-orbit mode
- 🔄 **1-Hand / 2-Hand toggle** — Switch gesture complexity on the fly
- 🤚 **Left-Handed support** — Dominant hand toggle for accessibility

## 🚀 Live Demo

👉 **[Launch AETHER](https://YOUR_USERNAME.github.io/3D-Gesture/)**

> Replace `YOUR_USERNAME` with your GitHub username after deployment.

## 🎮 How to Use

1. Open the live demo in a modern browser (Chrome/Edge recommended)
2. Allow camera access when prompted
3. Use hand gestures to control the 3D particle system:

### Single-Hand Gestures
| Gesture | Action |
|---|---|
| Move wrist | Orbit/rotate the particle formation |
| Pinch (thumb + index) | Zoom in/out |
| Roll palm | Z-axis rotation |

### Two-Hand Gestures
| Gesture | Action |
|---|---|
| Spread/contract hands | Scale the formation |
| Tilt like steering wheel | Roll the shape |
| Move hands in parallel | Pan 3D space |
| Open both fists | Particle explosion/reform |
| Clap hands together | Reset view & orientation |
| Pinch both hands | Freeze/lock view |
| Left still + right orbit | Precision orbit (1.5× sensitivity) |
| Left pinch + right orbit | Simultaneous zoom + rotate |
| Left fist + right open | Cycle through shape presets |

## 🛠️ Tech Stack

- **[Three.js](https://threejs.org/)** (r128) — WebGL 3D rendering
- **[MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands)** — Real-time hand landmark tracking
- **Vanilla HTML/CSS/JS** — Zero dependencies, zero build step

## 📋 Requirements

- Modern browser with WebGL support (Chrome, Edge, Firefox)
- Webcam for gesture control (optional — mouse fallback available)
- HTTPS connection (required for camera access; GitHub Pages provides this)

## 📄 License

MIT
