# ChronoWorm - Space Snake Game

A modern, space-themed snake game with stunning visual effects, AI opponents, and cross-platform support. Navigate through the cosmos as a glowing space worm, collect cosmic energy, and avoid other space creatures in this immersive HTML5 canvas game.

## 🎮 Features

### ✨ Core Gameplay
- **Space-Themed Snake Mechanics**: Control a glowing space worm through a cosmic arena
- **AI Opponents**: Compete against 50 intelligent space worms with unique behaviors
- **Boost System**: Activate boost for speed at the cost of worm length
- **Dynamic Food System**: Collect colorful cosmic energy orbs to grow
- **Collision System**: Avoid walls, yourself, and other space worms

### 🎨 Visual Experience
- **Animated Worm Skins**: Multiple cosmic patterns (Nebula, Galaxy, Stars, Comet)
- **Particle Effects**: Glowing trails and food orbs with dynamic lighting
- **Parallax Starfield**: Animated background with depth effect
- **Grid System**: Cosmic grid that enhances spatial awareness
- **UI Glow Effects**: Neon-inspired interface with smooth animations

### 🎵 Audio Immersion
- **Sound Effects**: 
  - `eat.mp3` - Collecting cosmic energy
  - `die.mp3` - Game over scenario
  - `boost.mp3` - Boost activation (looping)
  - `kill.mp3` - Eliminating AI opponents

### 📱 Cross-Platform Support

**There is some glitches will be fixed soon**

## 🚀 How to Play

### Basic Controls
**Desktop:**
- Move mouse to steer your space worm
- Hold mouse button to activate boost
- Press `P` or `Escape` to pause

**Mobile:**
- Use virtual joystick (bottom-left) to steer
- Tap boost button (bottom-right) to activate boost

### Game Mechanics
1. **Movement**: Steer your worm to collect colorful food orbs
2. **Growth**: Each collected orb increases your worm's length and score
3. **Boost**: Activate boost for speed (consumes worm length)
4. **Survival**: Avoid collisions with walls, yourself, and AI worms
5. **Elimination**: Destroy AI worms by colliding with their bodies

### Scoring
- **+10 points** per food orb collected
- **Bonus points** for eliminating AI opponents
- Score displayed as: `(Current Length - 10) × 10`

## 🛠️ Installation

### Quick Start
1. Download all project files:
   - `index.html`
   - `eat.mp3`
   - `die.mp3`
   - `boost.mp3`
   - `kill.mp3`

2. Open `index.html` in a modern web browser

### File Structure
```
chronoworm/
├── index.html          # Main game file
├── eat.mp3            # Food collection sound
├── die.mp3            # Game over sound
├── boost.mp3          # Boost activation sound
├── kill.mp3           # AI elimination sound
└── README.md          # This file
```

### Requirements
- Modern web browser with HTML5 support
- JavaScript enabled
- Audio support for sound effects
- Recommended: Chrome, Firefox, Safari, or Edge

## 🎯 Game Screens

### Start Screen
- Player name input (max 12 characters)
- Cosmic-themed interface
- Enter key support for quick start

### Game Screen
- Real-time score display
- AI bot counter
- Dynamic cosmic background
- Responsive game arena (3000×3000 world)

### Pause Screen
- Game state preservation
- Quick resume functionality
- Visual pause indicators

### Game Over Screen
- Final score display
- Death reason explanation
- Quick restart option

## 🔧 Technical Details

### Technologies Used
- **HTML5 Canvas** for rendering
- **CSS3** for UI and animations
- **Vanilla JavaScript** for game logic
- **Web Audio API** for sound management

### Performance Features
- Efficient collision detection
- Object pooling for food items
- Optimized rendering with viewport culling
- Frame rate independent movement

### Mobile Optimization
- Touch event handling
- Virtual control system
- Responsive canvas scaling
- Performance-optimized for mobile devices

## 🎨 Customization

### Worm Skins
The game features multiple animated skin patterns:
- **Nebula**: Purple/blue/pink shifting colors
- **Galaxy**: Blue/green cosmic patterns
- **Stars**: White/yellow sparkle effects
- **Comet**: Orange/red tail effects

### Game Constants
Easy-to-modify variables in the script:
```javascript
const WORLD_SIZE = 3000;      // Game world dimensions
const MAX_FOOD = 500;         // Maximum food items
const BOT_COUNT = 50;         // Number of AI opponents
const BASE_SPEED = 3;         // Normal movement speed
const BOOST_SPEED = 6;        // Boosted movement speed
```

## 🐛 Known Issues

- **Audio Restrictions**: Browser may require user interaction before playing sounds
- **Mobile Performance**: May experience frame drops on older devices
- **Touch Accuracy**: Small hitboxes on mobile devices

## 🚀 Future Enhancements

- [ ] Leaderboard system
- [ ] Power-up items
- [ ] Multiple game modes
- [ ] Worm customization options
- [ ] Level progression system
- [ ] Multiplayer support

## 📝 Development Notes

### Code Structure
- Modular game loop system
- Object-oriented design for game entities
- Event-driven input handling
- Separation of concerns between rendering and logic

### Browser Compatibility
- Chrome 70+ ✅
- Firefox 65+ ✅
- Safari 12+ ✅
- Edge 79+ ✅

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for:
- Bug fixes
- Performance improvements
- New features
- Documentation updates

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Red4**
- Game concept and development
- Visual design and effects
- Audio integration

## 🙏 Acknowledgments

- Inspired by classic snake games with modern twists
- Built with pure web technologies (no frameworks)
- Special thanks to the HTML5 gaming community

---

**Enjoy exploring the cosmos with ChronoWorm!** 🌌

*For questions or support, please open an issue in the project repository.*
