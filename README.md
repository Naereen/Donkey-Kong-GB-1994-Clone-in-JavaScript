# 🍌 Donkey Kong GB 1994 Clone in JavaScript

A browser-based recreation of the classic **Donkey Kong** arcade game inspired by the 1994 Game Boy version. Built entirely with vanilla JavaScript and HTML5 Canvas API, this game brings the nostalgic platformer action to your web browser!

## 🎮 Game Description

Help Mario climb the construction site platforms to rescue Pauline from Donkey Kong! Navigate through dangerous barrels, climb ladders, and collect hammers to defend yourself in this faithful recreation of one of gaming's most iconic titles.

## ✨ Features

- **Classic Arcade Gameplay**: Experience the authentic Donkey Kong platforming action
- **Sprite-based Animation**: Smooth character animations using sprite sheets
- **Multiple Game Elements**:
  - Moving platforms and ladders
  - Rolling barrels (orange and blue variants)
  - Power-up hammers for temporary invincibility
  - Enemy obstacles and fire hazards
  - Score tracking system
  - Game over and victory screens
- **Sound Effects**: Original-style audio including:
  - Walking sounds
  - Theme music
  - Collision/death sounds
- **Collision Detection**: Precise hitbox detection for all game objects
- **Responsive Controls**: Keyboard-based controls for movement and jumping
- **Local High Score**: Tracks your best score using browser localStorage

## 🛠️ Technologies Used

- **HTML5 Canvas**: For 2D graphics rendering
- **Vanilla JavaScript (ES6)**: No frameworks or libraries required
- **CSS**: Basic styling for canvas layout
- **Web Audio API**: For sound effects and music playback

## 📁 Project Structure

```
Donkey-Kong-GB-1994-Clone-in-JavaScript/
├── index.html              # Main HTML file
├── js/
│   ├── script.js          # Main game loop and logic
│   ├── mario.js           # Mario character class and controls
│   ├── barrel.js          # Barrel enemy objects
│   ├── platform.js        # Platform structures
│   ├── ladder.js          # Ladder objects
│   ├── enemy.js           # Enemy characters
│   ├── hammer.js          # Power-up hammer objects
│   └── obsctacle.js       # Obstacle elements (note: filename has typo)
├── images/                 # All game sprites and graphics
│   ├── smallmariosheet-3.png
│   ├── barrelspritesheet.png
│   ├── donkeykongbanner.png
│   └── ... (50+ sprite files)
└── sounds/                 # Audio files
    ├── theme.wav
    ├── walking2.wav
    └── death.wav
```

## 🚀 Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Naereen/Donkey-Kong-GB-1994-Clone-in-JavaScript.git
   cd Donkey-Kong-GB-1994-Clone-in-JavaScript
   ```

2. **Open in browser**:
   - Simply open `index.html` in your web browser
   - Or use a local web server:
     ```bash
     # Python 3
     python -m http.server 8000
     
     # Python 2
     python -m SimpleHTTPServer 8000
     
     # Node.js (with http-server)
     npx http-server
     ```
   - Navigate to `http://localhost:8000` in your browser

3. **Play the game**:
   - Press **Enter** on the start screen to begin
   - Use keyboard controls to navigate

## 🎯 How to Play

### Objective
Guide Mario up the platforms to reach Pauline at the top while avoiding barrels and obstacles thrown by Donkey Kong.

### Controls

| Key | Action |
|-----|--------|
| **Arrow Left** / **A** | Move Mario left |
| **Arrow Right** / **D** | Move Mario right |
| **Arrow Up** | Climb up ladders |
| **Arrow Down** | Climb down ladders |
| **Spacebar** | Jump |
| **Enter** | Start game / Retry after game over |

### Gameplay Tips

- **Avoid Barrels**: Orange barrels roll down platforms, while blue barrels fall vertically
- **Collect Hammers**: Grab hammers for temporary invincibility (9 seconds) to destroy barrels
- **Use Ladders Wisely**: Plan your route carefully to avoid falling barrels
- **Score Points**: 
  - +10 points for each barrel you destroy with a hammer
  - +100 points for reaching Pauline at the top
- **Win Condition**: Reach the top platform where Pauline is located (Y position ≤ 50)

## 🎨 Game Mechanics

### Character Physics
- **Gravity System**: Mario experiences realistic falling physics
- **Platform Collision**: Precise collision detection for platforms
- **Ladder Climbing**: Vertical movement system for ladders
- **Jump Mechanics**: Variable jump height based on platform position

### Enemy Behavior
- **Barrel Spawning**: Barrels spawn at regular intervals (3-4 seconds)
- **Rolling Barrels**: Follow platform paths and can climb down ladders
- **Blue Barrels**: Fall straight down from upper platforms
- **Fire Hazards**: Static fire obstacles on lower platforms

### Game States
1. **Start Screen**: Title screen with instructions
2. **Playing**: Active gameplay with barrel spawning
3. **Game Over**: Death screen with score display and retry option
4. **Victory**: Win screen when reaching Pauline

## 🎵 Audio Features

The game includes authentic sound effects:
- **Background Music**: Classic Donkey Kong theme (plays on start/game over screens)
- **Walking Sound**: Plays during Mario's movement
- **Collision Sound**: Triggered when Mario is hit by a barrel

## 💾 Save System

- High scores are automatically saved to browser localStorage
- Score persists across game sessions
- Resets only when browser cache is cleared

## 🖼️ Sprite Assets

The game features over 50 sprite images including:
- Mario animations (walking, jumping, hammer, death)
- Donkey Kong sprites
- Barrel variations and animations
- Platform and ladder graphics
- Pauline character sprite
- UI elements (banners, text)

## 🐛 Known Limitations

- Single level/stage implementation
- No multiplayer support
- Audio autoplay may be blocked by browser policies

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs via GitHub Issues
- Submit pull requests for improvements
- Suggest new features
- Improve documentation

## 📜 License

This project is a fan-made recreation for educational purposes. All original Donkey Kong characters and concepts are © Nintendo.

## 🙏 Credits

- **Original Game**: Nintendo (1981-1994)
- **Clone Developer**: [@Naereen](https://github.com/Naereen)
- **Technology**: HTML5 Canvas API, Vanilla JavaScript

## 🔗 Links

- **Repository**: [GitHub](https://github.com/Naereen/Donkey-Kong-GB-1994-Clone-in-JavaScript)
- **Original Game**: [Donkey Kong (Wikipedia)](https://en.wikipedia.org/wiki/Donkey_Kong)

---

**Enjoy the game! 🎮🍌**

*Press Enter to Start Your Adventure!*
