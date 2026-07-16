# FRUIT SLASH - Realistic Mobile Game

## Concept & Vision

Game slicing buah yang realistis dengan grafis indah, efek jus yang memukau, dan gameplay yang adiktif. Pemain menggeser jari untuk memotong buah yang muncul dari bawah layar. Visual yang realistis dengan pencahayaan dinamis, partikel jus, dan blade trail yang mulus.

**Feel**: Seru, memuaskan, adiktif - setiap slice terasa nyata dengan semburan jus dan partikel.

## Design Language

### Aesthetic
- **Style**: Modern realistic dengan sedikit stylization
- **Background**: Gradient langit sunset dengan awan parallax
- **Fruits**: Drawn dengan gradients, shadows, highlights untuk kesan 3D
- **Effects**: Juice splash, particle systems, blade trails

### Color Palette
- Primary: #FF6B35 (Orange)
- Secondary: #4ECDC4 (Teal)
- Accent: #FFE66D (Yellow)
- Background: Linear gradient sunset (#FF6B6B → #FFA07A → #87CEEB)
- Bomb: #2C3E50 (Dark)
- Text: #FFFFFF with shadows

### Typography
- Display: "Lilita One" (Google Fonts) - playful, bold
- Body: "Nunito" (Google Fonts) - readable, friendly

### Motion
- Smooth easing untuk fruit trajectories
- Physics-based gravity
- Particle physics untuk juice splashes
- Bezier curves untuk blade trails

## Features

### Core Gameplay
- Swipe to slice fruits
- 3 lives system (miss 3 fruits = game over)
- Combo system (slice multiple fruits quickly)
- Score multiplier based on combo

### Fruit Types
1. **Watermelon** - Green/red, large, 10 pts
2. **Orange** - Orange, medium, 5 pts
3. **Apple** - Red, small, 5 pts
4. **Banana** - Yellow, curved, 8 pts
5. **Kiwi** - Brown/green, small, 7 pts
6. **Grape** - Purple, tiny, 3 pts
7. **Coconut** - Brown/white, hard to hit, 15 pts
8. **Pineapple** - Yellow/brown, large, 12 pts

### Special Items
- **Star** ⭐ - Bonus 50 pts
- **Bomb** 💣 - Lose 1 life if sliced (don't slice!)

### Effects
- Juice splash particles on slice
- Blade trail following finger
- Fruit halves falling with rotation
- Screen shake on bomb
- Combo popup text
- Score popup on each slice

### Game Modes
- **Classic** - 3 lives, survive as long as possible
- **Zen** - No lives, play forever
- **Time Attack** - 60 seconds, max score

### Statistics
- Total fruits sliced
- Best combo
- High score
- Games played

## Technical

### Stack
- Pure HTML5 Canvas
- CSS3 for UI elements
- Web Audio API for sounds
- LocalStorage for persistence
- RequestAnimationFrame for smooth 60fps

### Architecture
- Single HTML file
- Modular JavaScript with classes
- Sprite-based rendering (drawn with canvas)
- Particle system manager
- Touch event handling with prediction
