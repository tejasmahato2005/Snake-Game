# 🐍 Snake Game (HTML, CSS & JavaScript — Single File)

A responsive, mobile-friendly Snake Game built entirely inside **one HTML file**.

---

## 📸 Screenshots

### In-game view  
![Snake gameplay](images/snake-play.png)

### Game over dialog  
![Snake game over](images/snake-gameover.png)

---

## 🚀 Features

- Single-file project (HTML + CSS + JS together)
- Responsive layout (desktop and mobile)
- Keyboard controls: Arrow keys / WASD
- Mobile swipe controls (touch)
- Start, Pause, Reset buttons
- Adjustable grid size (16×16, 20×20, 24×24)
- Speed options: Slow / Normal / Fast
- Game Over overlay with “Play again”
- Score tracking and smooth snake animation

---

## 🎮 Controls

### Desktop
- **Arrow keys / WASD** → Move snake  
- **Spacebar** → Pause / Resume  
- **Start / Pause / Reset** buttons → Control game state  

### Mobile
- **Swipe Up / Down / Left / Right** on the canvas → Change direction  

---

## 📁 Project Structure

```text
snake.html
README.md
images/
  ├── snake-play.png
  └── snake-gameover.png

▶️ How to Run

Save the file as snake.html.

Open it in any modern browser (Chrome, Firefox, Edge, Safari).

Play the game.

You can also use VS Code Live Server, but it is not required.

🧠 How It Works (Brief)

The board is a grid rendered on an HTML <canvas>.

The snake is an array of segments; the head moves each tick.

Eating food grows the snake and increases the score.

The snake wraps at the edges (no walls).

Self-collision triggers the Game Over overlay.

Swipe events on touch devices update the direction vector.

🛠 Customization

Grid size: change options in the <select id="gridSize"> element.

Speed: change values and labels in <select id="speed">.

Colors: edit CSS variables in the :root block:

:root {
  --bg: #0f1724;
  --panel: #0b1220;
  --accent: #16a34a;
  --muted: #94a3b8;
}

📜 License

Free to use, modify, and share for learning and personal projects.
