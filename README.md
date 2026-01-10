# 𖠞 أحمد الشياش - Ahmed Chayech

### The Ultimate Tunisian Shisha Smoking Game 💨🇹🇳

<p align="center">
  <img src="https://img.shields.io/badge/Made%20With-Three.js-black?style=for-the-badge&logo=three.js" alt="Three.js">
  <img src="https://img.shields.io/badge/Audio-Tone.js-purple?style=for-the-badge" alt="Tone.js">
  <img src="https://img.shields.io/badge/Language-Tunisian%20Derja-red?style=for-the-badge" alt="Tunisian">
  <img src="https://img.shields.io/badge/Platform-Mobile%20Friendly-green?style=for-the-badge" alt="Mobile">
  <br>
  <img src="https://github.com/faresk93/ahmed-shisha-game/actions/workflows/deploy.yml/badge.svg" alt="Deploy to GitHub Pages">
</p>

---

## DEMO <img width="100" height="100" alt="image" src="https://github.com/user-attachments/assets/03d7f6a4-bd33-4c17-8d9c-8eaee6265875" />

https://faresk93.github.io/ahmed-shisha-game/

## 🎮 About The Game

**Ahmed Chayech** (أحمد الشياش) is a fun, interactive shisha smoking simulator built with Three.js. Experience the authentic Tunisian café atmosphere with realistic 3D graphics, immersive sound effects, and hilarious Tunisian dialect expressions!

Whether you're missing the vibes of a Tunisian *kahwa* or just want a chill gaming experience, Ahmed Chayech brings the shisha lounge to your screen.

---

## ✨ Features

### 🍎 Shisha Flavor Selection
Choose your favorite flavor at the start of the game! Each flavor features unique visual effects:

| Flavor | Emoji | Smoke Color | Bowl Color |
|--------|-------|-------------|------------|
| تفاح (Apple) | 🍎 | Light Pink | Red |
| نعناع (Mint) | 🌿 | Light Green | Forest Green |
| عنب (Grape) | 🍇 | Light Purple | Purple |
| دلاع (Watermelon) | 🍉 | Light Pink | Sea Green |

### 🎨 Stunning 3D Graphics
- Beautifully crafted 3D shisha model with metallic gold accents
- Realistic glowing coal with dynamic ember particles
- Floating smoke particles and expanding smoke rings with flavor-specific colors
- Atmospheric lighting with warm Middle Eastern tones
- Animated backgrounds with pulsing gradients

### 🔊 Immersive Sound Design
| Sound | Description |
|-------|-------------|
| 💧 Bubbling | Authentic water pipe bubbling sounds |
| 💨 Smoke Puff | Breathy exhale effects |
| 🔥 Coal Sizzle | Crackling ember sounds |
| 🎵 Combo Chimes | Musical rewards for combos |
| ⭐ Perfect Ring | Magical sparkle arpeggio |
| 🎶 Ambient | Soft atmospheric drone |

### 🇹🇳 Authentic Tunisian Expressions
The game features genuine Tunisian Derja (dialect) phrases:

> **يا سلام!** - Ya Salam! (Wow!)
> 
> **برشا بنين!** - Barsha Bnin! (Very nice!)
> 
> **هذي هي!** - Hathi Hiya! (That's it!)
> 
> **طبرقلي!** - Tabargeli! (You amazed me!)
> 
> **كومبو خرافي!** - Combo Khorafi! (Legendary combo!)
> 
> **يعطيك الصحة!** - Ya3tik Essa7a! (Bless you!)

---

## 🕹️ How To Play

### Controls

| Button | Action |
|--------|--------|
| 💨 **Smoke Button** | Tap to take a puff and create smoke |
| 🔥 **Coal Button** | Tap to heat up the coals |
| 🔊 **Sound Toggle** | Mute/unmute game sounds |

### Gameplay Loop

1. **Choose your flavor** - Select from 4 authentic shisha flavors
2. **Start the game** - Tap "يلا نبداو!" (Let's go!)
3. **Smoke** - Tap the smoke button to puff and earn points
4. **Manage heat** - Keep the coals hot or game over!
5. **Build combos** - Chain puffs for multiplier bonuses
6. **Hit the golden zone** - Guide smoke rings through the target for +50 bonus points

### Scoring System

| Action | Points |
|--------|--------|
| Basic puff | 10 points |
| Combo x2 | 20 points |
| Combo x3 | 30 points |
| Combo x4 | 40 points |
| Combo x5+ | 50+ points |
| Golden ring | +50 bonus |

---

## 🛠️ Technical Stack

```
├── Three.js r128      → 3D rendering engine
├── Tone.js 14.8       → Web Audio synthesis
├── CSS3 Animations    → UI effects & transitions
├── WebGL              → Hardware-accelerated graphics
└── LocalStorage       → High score persistence
```

### Browser Support
- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers (iOS Safari, Chrome Android)

---

## 📱 Mobile Optimization

Ahmed Chayech is fully optimized for mobile devices with a no-scroll, full-screen experience:

- Touch-friendly large tap targets with responsive sizing
- Responsive layout that fits everything on screen without scrolling
- Dynamic viewport height (`100dvh`) for consistent mobile experience
- Optimized particle count for smooth performance
- Disabled zoom and scroll for immersive gameplay
- High DPI display support
- Special landscape mode layout adjustments
- CSS clamp() for fluid, adaptive typography and spacing

---

## 🎨 Design Philosophy

The visual design draws inspiration from:

- **Traditional Tunisian aesthetics** - Gold and burgundy color palette
- **Middle Eastern patterns** - Subtle geometric overlays
- **Modern gaming UI** - Clean, readable interfaces
- **Luxury hookah lounges** - Ambient, moody lighting

Typography uses **Lalezar** for Arabic display text and **Tajawal** for body content, ensuring authentic regional character.

---

## 🚀 Getting Started

### Quick Start
Simply open `index.html` in any modern web browser!

### Local Development
```bash
# Clone the repository
git clone https://github.com/faresk93/ahmed-shisha-game.git
cd ahmed-shisha-game

# Open in browser
open index.html

# Or serve locally
python -m http.server 8000
# Then visit http://localhost:8000
```

### 🔄 Deployment

This project uses **GitHub Actions** for automatic deployment. Every merge to the main branch triggers automatic deployment to GitHub Pages.

The live game is available at: https://faresk93.github.io/ahmed-shisha-game/

---

## 📊 Game Mechanics

### Heat System
- Starting heat: **80%**
- Heat loss per puff: **-3%**
- Passive heat decay: **-1% every 0.5s**
- Heat added per coal tap: **+15%**
- Game over at: **0%**

### Combo System
- Combos decay after **2 seconds** of inactivity
- Maximum combo multiplier: **x5+**
- Combo triggers special Tunisian phrases

### Smoke Rings
- **40% base chance** to create a ring per puff
- Chance increases with combo level
- Rings that pass through the golden zone earn bonus points

---

## 🌟 Tips & Tricks

1. **Balance your taps** - Don't spam smoke, manage your heat!
2. **Watch the heat meter** - Add coal before it gets critical
3. **Chain combos** - Quick successive puffs build multipliers
4. **Aim for gold** - Smoke rings through the golden zone = big points
5. **Listen for warnings** - Audio cues alert you to low heat

---

## 🤝 Contributing

Feel free to fork, modify, and improve! Ideas for future features:

- [x] ~~Multiple shisha flavors with unique effects~~ ✅ Implemented!
- [ ] Achievements system
- [ ] Multiplayer smoke ring battles
- [ ] More Tunisian phrases and regional dialects
- [ ] Customizable shisha designs
- [ ] Leaderboard system
- [ ] Additional shisha flavors

---

## 📜 License

This project is open source and available for personal and educational use.

---

## 🙏 Acknowledgments

- Inspired by Tunisian café culture and the art of shisha
- Built with love for the Tunisian community worldwide
- Special thanks to the Three.js and Tone.js communities

---

<p align="center">
  <strong>Made with shisha ❤️ love by Fares AI to Ahmed Chayech</strong>
  <br><br>
  <strong>🇹🇳 Made with ❤️ for Tunisia 🇹🇳</strong>
  <br>
  <em>يعيشك! - Ya3ichek!</em>
</p>

---

<p align="center">
  <sub>⚠️ This is a game for entertainment purposes only. Always enjoy shisha responsibly.</sub>
</p>
