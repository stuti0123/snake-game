# 🐍 Innovative Snake Game

A modern, feature-rich implementation of the classic Snake game with multiple game modes, power-ups, and advanced visual effects. Built with vanilla JavaScript and HTML5 Canvas for optimal performance and compatibility.

![Snake Game Demo](https://img.shields.io/badge/Game-Live%20Demo-brightgreen?style=for-the-badge)
[![GitHub Pages](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://YOUR_USERNAME.github.io/snake-game/)

## 🎮 Live Demo

**[Play the Game Here!](https://stuti0123.github.io/snake-game/)**

## ✨ Features

### 🎯 Multiple Game Modes
- **Classic Mode**: Traditional gameplay with wall wrap-around mechanics
- **Speed Rush**: Progressive difficulty with increasing snake speed
- **Survival Mode**: Strategic gameplay with procedurally generated obstacles
- **Rainbow Mode**: Visual spectacle with dynamic color-changing snake

### ⚡ Advanced Game Mechanics
- **Power-up System**: Speed boost, score multiplier, and ghost mode abilities
- **Dynamic Particle Effects**: Visual feedback for food consumption and interactions
- **Progressive Difficulty**: Level-based scaling with increasing challenges
- **Collision Detection**: Optimized algorithms for smooth gameplay

### 🎨 Modern UI/UX
- **Glassmorphism Design**: Contemporary visual aesthetics with backdrop blur effects
- **Responsive Layout**: Optimized for various screen sizes and devices
- **Smooth Animations**: CSS3 transitions and keyframe animations
- **Audio Feedback**: Web Audio API integration for immersive sound effects

### 💾 Data Management
- **High Score Persistence**: Local storage implementation for score tracking
- **Game State Management**: Efficient handling of multiple game states
- **Real-time Statistics**: Live updates for score, level, and achievements

## 🛠️ Technical Implementation

### Technologies Used
- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Graphics**: HTML5 Canvas API for 2D rendering
- **Audio**: Web Audio API for dynamic sound generation
- **Storage**: Browser Local Storage for data persistence
- **Deployment**: GitHub Pages for static hosting

### Key Technical Features
- **Object-Oriented Architecture**: Modular class-based structure for maintainability
- **Game Loop Optimization**: Efficient rendering and update cycles
- **Memory Management**: Particle system with automatic cleanup
- **Cross-Browser Compatibility**: Vanilla JavaScript for maximum compatibility
- **Performance Optimization**: Minimized DOM manipulation and optimized Canvas operations

## 🚀 Getting Started

### Prerequisites
- Modern web browser with HTML5 Canvas support
- No additional dependencies required

### Local Setup
1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/snake-game.git
   cd snake-game
   ```

2. **Launch the game**
   ```bash
   # Simply open index.html in your browser
   # Or use a local server (recommended)
   python -m http.server 8000
   # Navigate to http://localhost:8000
   ```

### Controls
- **Movement**: WASD keys or Arrow keys
- **Start Game**: Click the Start button or press any movement key
- **Pause**: Click Pause button
- **Reset**: Click Reset button

## 🎮 Gameplay

### Objective
Guide the snake to eat food while avoiding collisions with walls (in non-classic modes), obstacles, and the snake's own body.

### Scoring System
- **Normal Food**: 10 points
- **Special Food**: 20 points (golden food with enhanced visual effects)
- **Power-up Multiplier**: 2x points when score multiplier is active
- **Level Progression**: Every 100 points increases the level

### Power-ups
- **⚡ Speed Boost**: Temporarily increases snake movement speed
- **💎 Score Multiplier**: Doubles points for a limited duration
- **👻 Ghost Mode**: Allows passing through walls and obstacles

## 🏗️ Architecture

### Core Components
```
SnakeGame Class
├── Game State Management
├── Rendering Engine (Canvas)
├── Input Handler
├── Collision Detection
├── Audio Manager
├── Particle System
└── UI Controller
```

### Code Structure
- **Modular Design**: Single-responsibility principle implementation
- **Event-Driven Architecture**: Efficient event handling and state management
- **Separation of Concerns**: Clear distinction between game logic, rendering, and UI

## 🔧 Customization

The game is designed for easy customization:

- **Grid Size**: Modify `gridSize` property
- **Game Speed**: Adjust `gameSpeed` for different difficulties
- **Colors**: Customize snake, food, and UI colors
- **Power-ups**: Add new power-up types and effects
- **Game Modes**: Implement additional gameplay variants


