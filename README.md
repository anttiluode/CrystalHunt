# 💎 Crystal Hunt - Gesture-Controlled Flight Collection Game

![Crystal Hunt](./crystal_hunt.png)

**Fly through infinite fractal worlds using your body as the controller!** Collect magical crystals to survive in this unique gesture-controlled flight game that combines computer vision, procedural generation, and spatial audio.

## 🚀 [Play Now](https://anttiluode.github.io/crystalhunt/)

> **Note**: Requires webcam access for gesture controls. Works best in Chrome/Edge browsers.

## 🎮 Game Overview

Crystal Hunt is an innovative browser-based game where players use **body movements** to fly through procedurally generated 3D worlds, collecting crystals to maintain their life energy. Each crystal produces a unique sound based on its mathematical properties, creating a synesthetic gameplay experience.

### 🎯 Objective
- **Collect crystals** before your life energy runs out
- **Survive as long as possible** in the infinite fractal landscape
- **Master gesture controls** to become the ultimate Crystal Hunter

### ✨ Key Features
- **🤲 Gesture Control**: Use your hands and head to control flight
- **🌍 Infinite World**: Procedurally generated fractal mountains and forests
- **💎 Dynamic Crystals**: Each crystal has unique visual and audio properties
- **🎵 Spatial Audio**: Procedural sound generation based on crystal mathematics
- **⚡ Energy Management**: Collect crystals to survive
- **🏆 High Scores**: Beat your personal best (stored locally)

## 🎮 How to Play

### 🎛️ Gesture Controls
| Gesture | Action | Description |
|---------|--------|-------------|
| **✋ Left Hand Height** | Speed Control | Raise hand = faster flight (up to 240 km/h) |
| **🤲 Right Hand Position** | Steering | Move hand left/right/up/down to steer |
| **🗣️ Head Tilt** | Camera Roll | Tilt head for banking turns |

### ⌨️ Keyboard Controls (Testing/Backup)
| Key | Action |
|-----|--------|
| `W/S` or `↑/↓` | Speed up/down |
| `A/D` or `←/→` | Steer left/right |
| `Q/E` | Roll left/right |
| `R` | Reset position |

### 💎 Crystal Types
- **🔵 Normal Crystals**: +20 energy, +50 points
- **🟡 Super Crystals**: +35 energy, +100 points (rare)

## 🛠️ Technical Features

### 🎨 Graphics & Rendering
- **Three.js** for 3D graphics and WebGL rendering
- **Procedural terrain** using multi-octave Simplex noise
- **Dynamic lighting** with shadow mapping
- **Particle effects** and crystal animations

### 👁️ Computer Vision
- **MediaPipe Pose** for real-time body tracking
- **Gesture recognition** for natural movement controls
- **Webcam integration** with privacy-first processing

### 🎵 Audio System
- **Web Audio API** for procedural sound generation
- **Frequency-based** crystal collection sounds
- **Spatial audio** effects

### 🌍 World Generation
- **Infinite chunked terrain** with level-of-detail management
- **Fractal noise algorithms** for realistic mountain generation
- **Procedural forest placement**
- **Dynamic crystal spawning**

### 📋 Requirements
- **Modern browser** (Chrome 88+, Firefox 85+, Safari 14+)
- **Webcam** for gesture controls
- **HTTPS connection** (required for camera access)
- **Good lighting** for optimal pose detection

## 🎯 Game Mechanics

### ⚡ Energy System
- Starts with **100% life energy**
- **Drains continuously** over time (0.8% per second)
- **Restore energy** by collecting crystals
- **Game over** when energy reaches 0%

### 🎮 Flight Physics
- **Gesture-responsive** flight controls
- **Momentum-based** movement with inertia
- **Altitude limits** to keep players in the game world
- **Smooth camera** transitions and banking

### 🏆 Scoring
- **Base points** for crystal collection
- **Bonus points** for rare crystals
- **Survival time** bonus
- **Local leaderboard** (browser storage)

## 🎨 Visual Design

### 🌈 Art Style
- **Low-poly aesthetic** with vibrant colors
- **Procedural landscapes** inspired by fractal geometry
- **Glowing crystal effects** with particle systems
- **Atmospheric lighting** and fog effects

### 🎭 UI/UX
- **Minimalist HUD** showing essential information
- **Real-time gesture feedback** for control validation
- **Energy visualization** with color-coded health bar
- **Accessibility considerations** for different lighting conditions

## 🔊 Audio Design

### 🎵 Procedural Audio
Each crystal generates sound based on its mathematical properties:
- **Frequency mapping** from crystal position and type
- **Harmonic progressions** for collection sequences
- **Spatial audio** effects based on crystal proximity

## 🧪 Technical Architecture

Crystal Hunt/
├── index.html          # Main game file
├── README.md          # This file


### 🏗️ Core Systems
1. **Gesture Recognition Pipeline**
   - MediaPipe pose detection
   - Hand/head tracking
   - Movement interpretation

2. **3D World Engine**
   - Three.js scene management
   - Procedural terrain generation
   - Dynamic object spawning

3. **Game Logic Controller**
   - Energy management
   - Score tracking
   - Collision detection

4. **Audio Engine**
   - Procedural sound synthesis
   - Spatial audio processing

## 🐛 Known Issues & Limitations

- **Camera calibration** may require adjustment in different lighting
- **Performance** varies with device capabilities
- **Gesture sensitivity** may need fine-tuning for different users
- **Browser compatibility** limited to modern browsers with WebRTC support

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

### 🛠️ Technologies Used
- **[Three.js](https://threejs.org/)** - 3D graphics library
- **[MediaPipe](https://mediapipe.dev/)** - Computer vision framework
- **[Simplex Noise](https://github.com/jwagner/simplex-noise.js)** - Procedural generation
- **[Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)** - Audio synthesis

---

**Happy Crystal Hunting!** 💎✨🚀
