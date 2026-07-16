# 🍉 Fruit Slash - Realistic Mobile Game

<p align="center">
  <img src="https://img.shields.io/badge/Status-Live-brightgreen?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/Platform-Mobile%20%7C%20Web-blue?style=for-the-badge" alt="Platform">
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/PWA-Ready-orange?style=for-the-badge" alt="PWA">
</p>

Game slicing buah yang **realistis dan indah** dengan grafis 3D-like, efek jus yang memukau, dan gameplay yang adiktif!

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎨 **Realistic Graphics** | Buah dengan gradients, shadows, highlights |
| 💦 **Juice Effects** | Partikel jus dan splash saat memotong |
| ⚔️ **Blade Trail** | Jejak blade yang mulus mengikuti swipe |
| 🍎 **8 Fruit Types** | Watermelon, Orange, Apple, Banana, Kiwi, Grape, Coconut, Pineapple |
| 💣 **Bomb Hazard** | Hindari bom atau kehilangan nyawa! |
| ⭐ **Bonus Stars** | Kumpulkan bintang untuk bonus 50 poin |
| 🔥 **Combo System** | Slice cepat untuk combo multiplier |
| ❤️ **3 Lives** | Sistem nyawa (Classic mode) |
| 🎵 **Sound Effects** | Audio feedback yang memuaskan |
| 📊 **Statistics** | Lacak performa kamu |
| 🌅 **Beautiful Background** | Gradient sunset dengan awan parallax |

## 🎮 Game Modes

| Mode | Description |
|------|-------------|
| **🎯 Classic** | 3 nyawa, bertahan mungkin! |
| **🧘 Zen** | Main selamanya, tanpa batas |
| **⏱️ Time Attack** | 60 detik, raih skor tertinggi! |

## 🍎 Fruit Types

| Fruit | Points | Difficulty |
|-------|--------|------------|
| 🍉 Watermelon | 10 | Large & Slow |
| 🍊 Orange | 5 | Medium |
| 🍎 Apple | 5 | Small & Fast |
| 🍌 Banana | 8 | Curved |
| 🥝 Kiwi | 7 | Small |
| 🍇 Grape | 3 | Tiny |
| 🥥 Coconut | 15 | Hard to hit |
| 🍍 Pineapple | 12 | Large |

## 🚀 Quick Start

### Local Development
```bash
# Open index.html in browser
# Or use a local server:
python -m http.server 8000
# Then visit http://localhost:8000
```

### GitHub Pages
Game sudah di-host di: https://antono4.github.io/neon-strike-game/

## 📱 Installation (PWA)

1. Buka game di browser HP
2. Chrome/Android: Menu → "Add to Home Screen"
3. Safari/iPhone: Share → "Add to Home Screen"

## 🛠️ Tech Stack

- HTML5 Canvas
- CSS3 Animations
- Vanilla JavaScript
- Web Audio API
- LocalStorage
- GitHub Pages

## 🎯 How to Play

1. **Swipe** 👆 Geser jari untuk memotong buah
2. **Slice** 🍉 Potong buah untuk poin
3. **Combo** 🔥 Slice cepat untuk multiplier
4. **Avoid** 💣 Jangan potong bom!
5. **Collect** ⭐ Kumpulkan bintang untuk bonus

## 📁 Project Structure

```
neon-strike-game/
├── index.html      # Main game file
├── manifest.json   # PWA manifest
├── README.md       # Documentation
└── SPEC.md        # Game specification
```

## 🔧 Customization

### Change Gravity
```javascript
CONFIG.GRAVITY = 0.4; // Higher = faster falling
```

### Change Spawn Rate
```javascript
CONFIG.SPAWN_INTERVAL = 800; // milliseconds
```

### Add New Fruits
```javascript
FRUITS.push({
    name: 'mango',
    color: '#F39C12',
    innerColor: '#FDEBD0',
    radius: 42,
    points: 8,
    velocity: { min: 14, max: 20 }
});
```

## 📈 Statistics Tracked

- Games Played
- Best Combo
- Total Fruits Sliced
- High Score

## 🎨 Visual Effects

- **Juice Splash**: Particles + puddle when slicing
- **Blade Trail**: Smooth white trail following swipe
- **Fruit Halves**: Physics-based falling halves
- **Combo Popups**: Animated score displays
- **Background**: Parallax clouds + gradient sky

## 🤝 Contributing

1. Fork repository
2. Create branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes
4. Push to branch
5. Open Pull Request

## 📄 License

MIT License - Free to use!

---

<p align="center">
  Made with ❤️ for fruit lovers 🍎🍉🍊
</p>
