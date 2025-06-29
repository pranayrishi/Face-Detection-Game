# 🎮 Wave Survival Shooter
### *Mood-Adaptive Survival Game with Facial Recognition*

[![Game Demo](https://img.shields.io/badge/▶️%20Watch%20Demo-YouTube-red?style=for-the-badge&logo=youtube)](https://youtu.be/JfF-A3EYfqs)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![MediaPipe](https://img.shields.io/badge/MediaPipe-0078D4?style=flat-square&logo=google&logoColor=white)](https://mediapipe.dev/)
[![WebGL](https://img.shields.io/badge/WebGL-990000?style=flat-square&logo=webgl&logoColor=white)](https://www.khronos.org/webgl/)

## 🌟 Overview

**Wave Survival Shooter** is an innovative top-down survival game that uses real-time facial expression detection to dynamically adapt gameplay difficulty and challenge. Built with vanilla JavaScript and HTML5 Canvas, this game creates a personalized gaming experience that responds to your emotional state.

### 🎥 **[▶️ Watch the Game Demo on YouTube](https://youtu.be/JfF-A3EYfqs)**

---

## ✨ Key Features

### 🎭 **Real-Time Mood Detection**
- **Facial Recognition Integration** using MediaPipe algorithms
- **Dynamic Difficulty Adjustment** based on player engagement
- **Emotional State Tracking** (Happy, Sad, Neutral, Bored, Surprised)
- **Adaptive Gameplay Mechanics** that respond to player mood

### ⚡ **Advanced Combat System**
- **Continuous Auto-Fire** with weapon-specific cooldowns
- **Smart Direction Control** - shoot where you move or aim
- **6 Unique Weapons** with distinct characteristics
- **Progressive Wave System** with increasing difficulty

### 🎯 **Professional Game Design**
- **Retro Sci-Fi Aesthetic** with glowing neon elements
- **Particle Effects System** for explosions and visual feedback
- **Responsive Design** supporting desktop and mobile
- **Professional HUD** with real-time statistics

---

## 🎮 Gameplay Mechanics

### 🔫 **Weapons Arsenal**

| Weapon | Damage | Fire Rate | Ammo | Special Features |
|--------|--------|-----------|------|------------------|
| **PISTOL** | 10 | Normal | ∞ | Starter weapon, reliable |
| **SHOTGUN** | 25 | Slow | 20 | 5-bullet spread pattern |
| **RIFLE** | 30 | Fast | 30 | High damage, accurate |
| **MACHINE GUN** | 15 | Very Fast | 100 | Rapid continuous fire |
| **SNIPER** | 100 | Very Slow | 10 | Maximum damage, precise |
| **PLASMA** | 50 | Fast | 50 | Energy-based weapon |

### 👾 **Enemy Types**

- **🔴 BASIC** - Standard ground troops (20 HP, normal speed)
- **🟢 FAST** - Quick scouts (10 HP, high speed) 
- **🔵 TANK** - Armored units (80 HP, slow but tough)
- **🟣 BERSERKER** - Aggressive fighters (40 HP, balanced)
- **🟡 BOSS** - Massive star-shaped enemies (200 HP, special abilities)

### 🎭 **Mood-Based Adaptations**

#### 😊 **Happy/Engaged State**
- Normal progressive difficulty
- Standard wave progression
- Balanced enemy spawning

#### 😴 **Disengaged States** (Bored/Sad/Neutral)
- **⚡ BERSERK MODE ACTIVATION**
- 15 Berserker enemies spawn rapidly
- Boss enemy deployment
- Powerful weapon drops (Plasma & Machine Gun)
- Screen visual effects and chaos mode
- 20 seconds of maximum intensity

---

## 🎯 Controls

### 🖥️ **Desktop Controls**
```
WASD / Arrow Keys  →  Movement & Auto-Fire Direction
Mouse Movement     →  Aim when stationary
Walk Over Items    →  Collect weapons & health packs
```

### 📱 **Mobile Controls**
```
Touch & Drag       →  Movement control
Auto-Targeting     →  Automatic enemy engagement
Tap Items          →  Collection system
```

---

## 🚀 Installation & Setup

### **Option 1: Direct Play**
1. Download the HTML file
2. Open in any modern web browser
3. Allow camera permissions for mood detection
4. Start playing immediately!

### **Option 2: Local Server**
```bash
# Clone or download the project
git clone [your-repository-url]

# Navigate to project directory
cd wave-survival-shooter

# Serve with Python (if available)
python -m http.server 8000

# Or use Node.js live-server
npx live-server
```

### **System Requirements**
- **Browser**: Chrome 88+, Firefox 85+, Safari 14+, Edge 88+
- **Hardware**: Webcam (optional, for mood detection)
- **Performance**: 60fps capable device recommended

---

## 🧠 Technical Architecture

### **Core Technologies**
- **HTML5 Canvas** - 2D rendering engine
- **Vanilla JavaScript** - Game logic and mechanics
- **MediaPipe** - Facial recognition and expression analysis
- **WebRTC** - Camera access and video processing
- **CSS3** - Professional UI styling and animations

### **Game Systems**
```javascript
// Core game loop architecture
├── Player Movement System
├── Weapon Management System
├── Enemy AI & Spawning
├── Collision Detection
├── Particle Effects Engine
├── Mood Detection Algorithm
├── Dynamic Difficulty Adjustment
└── Performance Optimization
```

### **Performance Features**
- **Optimized Rendering** with requestAnimationFrame
- **Efficient Collision Detection** using spatial partitioning
- **Memory Management** with object pooling
- **Mobile Optimization** with touch event handling

---

## 🧪 Advanced Features

### **Facial Recognition Integration**
```javascript
// Mood detection pipeline
Camera Input → MediaPipe Analysis → Expression Classification → Gameplay Adaptation
```

### **Dynamic Difficulty System**
- **Real-time engagement monitoring**
- **Adaptive enemy spawning algorithms**
- **Contextual weapon distribution**
- **Progressive challenge scaling**

### **Health & Progression System**
- **Strategic health pack placement** (Wave 4+)
- **Weapon upgrade progression**
- **Score multiplier system**
- **Wave completion bonuses**

---

## 🎬 Demo & Showcase

### **📺 [Watch Full Gameplay Demo](https://youtu.be/JfF-A3EYfqs)**

**Video Highlights:**
- Complete gameplay walkthrough
- Mood detection system demonstration
- All weapons and enemies showcase
- Berserk mode activation examples
- Professional UI/UX presentation

---

## 🔧 Customization Options

### **Difficulty Tuning**
```javascript
// Modify these values in the game code:
const difficultySettings = {
    enemySpawnRate: 1.0,        // Enemy spawn frequency
    healthDropFrequency: 3,     // Health packs every N waves  
    weaponDropChance: 0.5,      // Weapon drop probability
    berserkModeDuration: 20000  // Chaos mode length (ms)
};
```

### **Mood Sensitivity**
```javascript
// Adjust facial recognition triggers:
const moodThresholds = {
    berserkActivation: 3,       // Consecutive negative expressions
    expressionHistorySize: 8,   // Analysis window size
    moodCheckInterval: 2000     // Detection frequency (ms)
};
```

---

## 🏆 Game Features Summary

✅ **Real-time facial expression recognition**  
✅ **6 unique weapons with distinct characteristics**  
✅ **5 enemy types including boss battles**  
✅ **Dynamic mood-based difficulty adjustment**  
✅ **Continuous auto-fire combat system**  
✅ **Progressive wave survival gameplay**  
✅ **Professional retro sci-fi visual design**  
✅ **Cross-platform compatibility (desktop/mobile)**  
✅ **Particle effects and visual feedback**  
✅ **Strategic health and weapon management**  

---

## 📄 License & Credits

### **Project License**
This project is available under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

### **Technology Credits**
- **MediaPipe** - Google's machine learning framework
- **HTML5 Canvas API** - 2D graphics rendering
- **WebRTC** - Real-time camera access

### **Development**
- **Game Design**: Complete survival shooter implementation
- **Facial Recognition**: MediaPipe integration for mood detection
- **Visual Effects**: Custom particle system and animations
- **Responsive Design**: Cross-platform compatibility

---

**🎮 Ready to survive the waves? [Start Playing Now!](index.html)**

*Built with passion for innovative gaming experiences and cutting-edge web technologies.*
