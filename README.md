# Voice-Commanded Snake Game 🐍🎙️

This project is a **proof of concept** designed to exercise voice recognition and JavaScript skills. It's a retro-style, voice-controlled Snake game implemented in JavaScript, HTML5, and TensorFlow.js. The game is fully hands-free, using voice commands to control the snake.

[Check live demo on this link](https://evandrosouza89.github.io/js-snake/index.html)

## 🎮 Features

- **Voice Commands**: Control the snake by saying **"Up"**, **"Down"**, **"Left"**, or **"Right"**.
- **Score Counter**: Track your score as you grow the snake by eating food.
- **Edge Wrapping**: The snake can wrap around the edges of the canvas.

## 🛠️ Technologies Used

- **HTML5 Canvas**: For rendering the game board and snake animations.
- **TensorFlow.js**: For voice command recognition via the pre-trained `speech-commands` model.
- **JavaScript**: Core game logic and voice recognition handling.
- **Google Fonts**: Retro arcade-style font.

## 📸 Screenshot

![Voice-Commanded Snake Game](/assets/screenshot.png)

## 🎙️ Usage

Once loaded, you’ll see:
1. The **score** in the top-left corner.
2. The **Detected Command** area showing the last recognized command.
3. The **Canvas** where the snake moves and consumes food items.

### Controls:
Speak the following commands to control the snake:
- **"Up"** - Moves the snake up
- **"Down"** - Moves the snake down
- **"Left"** - Moves the snake left
- **"Right"** - Moves the snake right

## 🤖 How It Works

1. **Voice Recognition**: TensorFlow.js `speech-commands` library captures spoken commands.
2. **Game Logic**: JavaScript processes each command, updating the snake’s direction.
3. **Snake Movement**: The snake moves based on the last recognized command, with food appearing randomly.

## 📝 Notes

- The TensorFlow.js model loads on page startup. If you don’t see commands being recognized, please check your microphone settings.
- Best experienced in a quiet environment for accurate voice command detection.

---

Enjoy playing the classic Snake game with a modern twist!
