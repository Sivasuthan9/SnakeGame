# 🎮 Snake Game on ILI9341 Display 🎮

This repository contains the implementation of a **Snake Game** developed for the **EE4360 - Embedded Systems Design and Programming** course assignment at the University of Moratuwa. The game is designed to be played on an ILI9341 display and controlled with a joystick, featuring **multiple levels** of gameplay and **interactive elements**. 

---

## 🚀 Game Features

### 🐍 Basic Gameplay
- **Snake Movement**: 🎮 Controlled by joystick input to navigate the snake.
- **Food Appearance**: 🍏 Food appears randomly, adding 1 point to the score with each item eaten.
- **Snake Growth**: 📈 The snake grows by 1 unit for each food item it consumes.
- **Edge Wrapping**: ↪️ If the snake crosses an edge, it reappears on the opposite side.
- **Game Over**: ❌ The game ends if the snake collides with itself.

### 🏆 Level Progression
- **Level 1**: Basic gameplay as described above.
- **Level 2**: ⚠️ A barrier (last digit of group number) appears; hitting it ends the game.
- **Level 3**: ⏳ Food disappears after 5 seconds, with a countdown timer.
- **Level 4**: 🟥 Red food appears, reducing score when eaten.
- **Level 5+**: 🐍 Snake speed increases by 20% with each level, with more red food items.

### 🎶 Additional Features
- **Sound Effects**: 🔊 Integrated buzzer adds immersive sound effects.
- **Menu**: 📜 Simple menu for starting a new game or viewing high scores.
- **High Score Saving**: 💾 High scores stored in EEPROM for future sessions.
- **Joystick Navigation**: 🕹️ Joystick controls for both menu and gameplay.

---

## 🛠️ Development Tools

- **Platform**: Wokwi-compatible development boards
- **Display**: ILI9341 TFT
- **Programming Framework**: Arduino IDE / PlatformIO
- **External Libraries**: Included as specified in the project files

---

## 📁 Project Structure

- `src/` - Source code files 📂
- `include/` - Header files 📄
- `lib/` - Libraries, if any 📚
- `README.md` - Project documentation 📜
- `demo.mp4` - 🎥 Gameplay demonstration (at least up to Level 4)
- `highscore.eeprom` - 🏆 EEPROM high score data

---

## 🚀 Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Lainitha/Snake_Game.git