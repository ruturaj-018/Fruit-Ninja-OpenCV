<div align="center">

# 🗡️ Fruit Ninja Enhanced 🍉

### *Motion-Controlled Gaming Meets Computer Vision*

![Python Version](https://img.shields.io/badge/python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![License](https://img.shields.io/badge/license-Apache%202.0-green?style=for-the-badge)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-red?style=for-the-badge&logo=opencv)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Enabled-orange?style=for-the-badge)
![Pygame](https://img.shields.io/badge/Pygame-2.x-yellow?style=for-the-badge)

```
╔═══════════════════════════════════════════════════════════════╗
║  🎮  Slice fruits with your hand movements using real-time   ║
║      computer vision tracking. No controllers needed! 🚀     ║
╚═══════════════════════════════════════════════════════════════╝
```

[🎮 Quick Start](#installation) • [🛠️ Tech Stack](#tech-stack) • [🤝 Contributing](#contributing)

</div>

---

## 🎯 Project Overview

<div align="center">

**Fruit Ninja Enhanced** transforms your webcam into a motion-controlled gaming experience! Wave your hand and watch as fruits explode in satisfying particle effects. This project showcases the perfect fusion of **computer vision**, **real-time tracking**, and **game development**.

</div>

### 🌟 Why This Project?

```
🎨 Beautiful particle effects    ⚡ Real-time hand tracking
🎯 Precision collision detection 🌈 Dynamic visual feedback  
🏆 Combo system & scoring        📹 Live camera preview
```

---

## 🎥 See It In Action

<div align="center">

![Fruit Ninja Gameplay](https://camo.githubusercontent.com/9519fd555440e419afa0dac73e568c7d028d1614a1a81a62eb01d71b016645a2/68747470733a2f2f7374617469632e7769787374617469632e636f6d2f6d656469612f6535383530385f34646330373066336563303234333366616633336535346261653164633330327e6d76322e706e67)

*Experience smooth hand tracking and satisfying fruit slicing action!*

</div>

---

## ✨ Features

<table>
<tr>
<td>

### 🎨 **Visual Excellence**
```
• Dynamic blade trail effects
• Particle explosion systems
• Smooth animations
• Fullscreen support
• Camera overlay preview
```

</td>
<td>

### 🧠 **Smart Tracking**
```
• Real-time hand detection
• Low-latency response
• Adaptive positioning
• Visual boundaries
• Gesture recognition
```

</td>
</tr>
<tr>
<td>

### 🎮 **Gameplay**
```
• Combo multiplier system
• Score tracking
• Multiple fruit types
• Sound effects
• Slicing mechanics
```

</td>
<td>

### ⚙️ **User Experience**
```
• Intuitive controls
• Cross-platform
• Easy setup
• Calibration guides
• Performance optimized
```

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

| 🔧 Technology | 💡 Purpose | 📦 Version |
|:-------------:|:----------:|:----------:|
| ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) **Python** | Core Language | `3.8+` |
| ![Pygame](https://img.shields.io/badge/-Pygame-yellow?style=flat) **Pygame** | Game Engine | `2.x` |
| ![OpenCV](https://img.shields.io/badge/-OpenCV-red?style=flat&logo=opencv) **OpenCV** | Computer Vision | `4.x` |
| ![MediaPipe](https://img.shields.io/badge/-MediaPipe-orange?style=flat) **MediaPipe** | Hand Tracking | `latest` |
| ![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy) **NumPy** | Calculations | `latest` |

</div>

---

## ⚙️ Installation

<div align="center">

### 🚀 Get Started in 3 Steps

</div>

```bash
# 1️⃣ Clone the repository
git clone https://github.com/ruturaj-018/Fruit-Ninja-OpenCV.git
cd Fruit-Ninja-OpenCV
```

```bash
# 2️⃣ Install dependencies
pip install -r requirements.txt
```

```bash
# 3️⃣ Launch the game
python Fruit-Ninja-OpenCV.py
```

### 📋 Prerequisites

```
✅ Python 3.8 or higher
✅ Working webcam
✅ Windows / macOS / Linux
```

---

## 🎮 How to Play

<div align="center">

| 🎯 Input | ⚡ Action |
|:--------:|:--------:|
| **👋 Hand Movement** | Control the katana |
| **✋ Slice Gesture** | Cut through fruits |
| **F Key** | Toggle fullscreen |
| **ESC Key** | Exit game |

</div>

### 🏆 Pro Tips

```
💡 Position yourself 1-2 feet from the camera
💡 Use bright, even lighting for best tracking
💡 Make deliberate slicing motions
💡 Chain combos for bonus points
💡 Keep hand within tracking boundaries
```

---

## 📚 How It Works

<div align="center">

### 🔄 System Architecture

</div>

```
    📹 WEBCAM INPUT
         ↓
    🤖 MEDIAPIPE HAND TRACKING
         ↓
    📊 COORDINATE MAPPING
         ↓
    🎯 COLLISION DETECTION
         ↓
    🎨 PYGAME RENDERING
         ↓
    💥 VISUAL EFFECTS
```

### ⚡ Processing Pipeline

| Step | Process | Technology |
|:----:|:-------:|:----------:|
| **1** | Frame Capture | OpenCV |
| **2** | Hand Detection | MediaPipe |
| **3** | Position Mapping | NumPy |
| **4** | Collision Logic | Pygame |
| **5** | Rendering | Pygame |
| **6** | Feedback Loop | 60+ FPS |

---

## 📁 Project Structure

```
🗡️ fruit-ninja-enhanced/
┃
┣━━ 📂 background/              ← 🖼️  Background images
┣━━ 📂 cursor/                  ← 🗡️  Katana cursor sprites
┣━━ 📂 fonts/                   ← 🔤 Game typography
┣━━ 📂 fruits/                  ← 🍎 Fruit graphics
┣━━ 📂 sounds/                  ← 🔊 Audio effects
┃
┣━━ 📄 fruit_ninja_enhanced.py  ← 🎮 Main entry point
┣━━ 📄 game_engine.py           ← ⚙️  Core mechanics
┣━━ 📄 game_objects.py          ← 🎯 Entity classes
┣━━ 📄 hand_tracking.py         ← 👋 CV & tracking
┣━━ 📄 requirements.txt         ← 📦 Dependencies
┣━━ 📄 LICENSE                  ← 📜 Apache 2.0
┗━━ 📄 README.md                ← 📖 Documentation
```

---

## 🎮 Game Elements

<div align="center">

### 📊 HUD Components

| Element | Description |
|:-------:|:-----------:|
| 🏆 **Score Counter** | Real-time point tracking |
| 🔥 **Combo Meter** | Multiplier visualization |
| 📹 **Camera Preview** | Live tracking feedback |
| 🎯 **Tracking Guides** | Boundary indicators |

### 🍎 Interactive Objects

```
🍉 Watermelon  •  🍎 Apple  •  🍌 Banana  •  🍊 Orange
🗡️ Blade Trail  •  ✨ Particles  •  💥 Explosions
```

</div>

---

## 💡 Performance Tips

<div align="center">

### 🌟 Optimal Setup Guide

</div>

| 🎯 Aspect | 💡 Recommendation |
|:---------:|:-----------------:|
| **🔦 Lighting** | Bright & even illumination |
| **📏 Distance** | 1-2 feet from camera |
| **🖼️ Background** | Plain, contrasting colors |
| **✋ Position** | Within tracking bounds |
| **⚡ Motion** | Deliberate slicing gestures |

### 🔧 Troubleshooting

```
🐌 Lag? → Close other webcam apps
🌙 Poor tracking? → Improve lighting
📷 No camera? → Check permissions
🖐️ Lost tracking? → Keep hand visible
```

---

## ⚠️ Known Issues

<div align="center">

```
⚡ Input lag on some systems (~50ms)
🌙 Tracking affected by low light
📹 Webcam init takes 2-3 seconds
🎨 Performance varies with backgrounds
```

*We're actively working on improvements!*

</div>

---

## 🤝 Contributing

<div align="center">

### 💪 Help Make This Better!

</div>

```
🐛 Report bugs          💡 Suggest features
🔧 Submit PRs           📖 Improve docs
🎨 Create sprites       🌟 Share feedback
```

### 📝 Quick Contribution Guide

```bash
# 1. Fork the repo
# 2. Create your feature branch
git checkout -b feature/AmazingFeature

# 3. Commit changes
git commit -m '✨ Add AmazingFeature'

# 4. Push to branch
git push origin feature/AmazingFeature

# 5. Open a Pull Request
```


---

## 🙏 Credits & Acknowledgments

<div align="center">

```
🎮 Original Concept  →  Halfbrick Studios (Fruit Ninja)
🤖 Hand Tracking    →  Google MediaPipe
🐍 Game Engine      →  Pygame Community
👁️ Computer Vision  →  OpenCV Project
```

</div>

---

<div align="center">

### ⭐ Star this repo if you found it helpful!

```
╔═════════════════════════════════════════════════════════╗
║  Made with 🍉 using Python, OpenCV & MediaPipe  ║
╚═════════════════════════════════════════════════════════╝
```

**[⬆ Back to Top](#-fruit-ninja-enhanced-)**

</div>

---

<div align="center">

![Visitors](https://api.visitorbadge.io/api/visitors?path=ruturaj-018/fruit-ninja-enhanced&label=Visitors&countColor=%23263759)
[![GitHub](https://img.shields.io/badge/GitHub-ruturaj--018-black?style=for-the-badge&logo=github)](https://github.com/ruturaj-018)
[![License](https://img.shields.io/badge/License-Apache%202.0-green?style=for-the-badge)](LICENSE)

</div>
