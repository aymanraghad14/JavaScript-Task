# 🎲 Dice Roll Game

A dynamic, interactive dice rolling game built with JavaScript, CSS3, and HTML5. Experience the thrill of rolling dice with smooth animations and engaging gameplay mechanics.

![Game Demo]<img width="1875" height="856" alt="Screenshot (734)" src="https://github.com/user-attachments/assets/9cf73b29-9359-4ddb-bebf-3d2cbb1de7e8" />
<img width="1876" height="901" alt="Screenshot (736)" src="https://github.com/user-attachments/assets/58ddda72-d418-410a-9b83-cd833bef0283" />



## 📋 Table of Contents

- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Getting Started](#-getting-started)
- [How to Play](#-how-to-play)
- [Game Rules](#-game-rules)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [License](#-license)

## ✨ Features

### 🎮 Core Gameplay
- **Two-Player Mode**: Competitive turn-based gameplay
- **Dynamic Scoring System**: Real-time score tracking and updates
- **Interactive Dice Rolling**: Click to roll with realistic animations
- **Win Detection**: Automatic game end when reaching target score

### 🎨 Visual & UX
- **3D Dice Animation**: Smooth rolling effects with CSS transforms
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile
- **Modern UI**: Clean, colorful interface with hover effects
- **Player Indicators**: Visual feedback for active player and game state

### ⚡ Technical Features
- ** JavaScript**: No external dependencies
- **Local Storage**: Save game progress
- **Keyboard Support**: Alternative controls for accessibility
- **Cross-Browser Compatible**: Works on all modern browsers

## 🛠️ Technologies Used
| **HTML5** | Structure & Semantics | - |
| **CSS3** | Styling & Animations | - |
| **JavaScript (ES6+)** | Game Logic & Interactivity | - |
| **CSS Grid/Flexbox** | Layout & Responsiveness | - |

## 🚦 Getting Started

## 🎯 How to Play

### Basic Controls
- **🎲 Roll Dice**: Click "Roll Dice" or press `R`
- **💾 Hold Score**: Click "Hold" or press `H` 
- **🔄 New Game**: Click "New Game" or press `N`

### Game Flow
1. Player 1 starts the game
2. Roll the dice to accumulate points
3. **Risk vs Reward**: Keep rolling for more points, but if you roll a 1, you lose all current points!
4. Hold your score to save it safely
5. First player to reach 100 points wins! 🏆

## 📖 Game Rules

### 🎯 Objective
Be the first player to reach **100 points** to win the game.

### 📜 Rules
- **Rolling**: Each turn, roll the dice to add points to your current score
- **The Danger of 1**: If you roll a 1, you lose all current (unsaved) points and your turn ends
- **Holding**: Click "Hold" to add your current points to your total score
- **Turn Switch**: After holding or rolling a 1, the turn switches to the other player
- **Winning**: First player to reach or exceed 100 total points wins

### 🎲 Strategy Tips
- **Early Game**: Take more risks when scores are low
- **Late Game**: Play conservatively when close to winning
- **Psychology**: Watch your opponent's score to decide your strategy

## 📁 Project Structure

```
dice-roll-game/
│
├── 📄 index.html          # Main HTML file
├── 🎨 styles.css          # CSS styles and animations
├── ⚡ script.js           # JavaScript game logic
├── 📷 images/             # Dice images and assets
│   ├── dice-1.png
│   ├── dice-2.png
│   └── ...
├── 📖 README.md           # Project documentation
└── 📄 LICENSE             # License file
```

## 🎨 Customization

### 🎯 Game Settings
```javascript
// In script.js - Modify these constants
const WINNING_SCORE = 100;    // Change target score
const ANIMATION_DURATION = 600; // Dice roll animation time
```

### 🎨 Styling
```css
/* In styles.css - Customize colors */
:root {
  --primary-color: #FF6B6B;
  --secondary-color: #4ECDC4;
  --accent-color: #45B7D1;
}
...

### 💡 Feature Requests
- Check existing issues first
- Clearly describe the feature and its benefits
- Consider implementation complexity


Made with ❤️ and lots of ☕
