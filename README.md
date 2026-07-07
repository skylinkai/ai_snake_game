# AI Snake

A polished, arcade-style Snake game built with Python and Pygame.

**Author:** [arindcha@gmail.com](mailto:arindcha@gmail.com)

## Requirements

- Python 3.8+
- [Pygame](https://www.pygame.org/)

```bash
pip install pygame
```

## How to Run

From the project folder:

```bash
python snakegame
```

### Run from Cursor / VS Code

1. Open **Run and Debug** (`Ctrl+Shift+D`)
2. Select **Run AI Snake**
3. Press **F5**

> This is a **desktop game** — it opens a Pygame window. It does not run in a browser.

## Controls

| Key | Action |
|-----|--------|
| Arrow Keys / WASD | Move the snake |
| P | Pause / Resume |
| R | Restart (on Game Over screen) |
| ESC | Back to menu / Quit from main menu |
| Mouse | Click menu buttons |

## Gameplay

- Eat red apples to grow and score points.
- Speed increases as you eat more apples.
- After **10 apples**, a neon **"You are the champ"** message appears.
- **Bonus fruit** (gold) appears randomly and disappears after a few seconds — worth extra points.
- **Obstacles** spawn after you reach higher scores.
- A **3-2-1 countdown** plays before each round.

### Difficulty

Choose from the main menu before playing:

- **Easy** — slower start
- **Normal** — balanced pace
- **Hard** — faster start

### Power-ups

| Power-up | Effect |
|----------|--------|
| **Slow Time** (S) | Snake moves slower for 8 seconds |
| **Double Score** (x2) | Earn double points for 8 seconds |
| **Ghost Mode** (G) | Pass through walls (wrap around) for 8 seconds |

## Menus

- **Play** — start a new game
- **High Scores** — view your best score
- **Controls** — keyboard and mouse help
- **Statistics** — games played, apples eaten, play time, and more
- **Achievements** — unlock milestones as you play
- **Quit** — exit the game

## Save Data

Progress is saved automatically to `snake_data.json` in the project folder:

- High score
- Games played
- Total apples eaten
- Best snake length
- Play time
- Unlocked achievements

## Features

- Smooth 60 FPS movement with animated snake and tail
- Rounded snake body, blinking eyes, and shadows
- Glowing apples with particle effects and screen shake
- Dark gradient background with animated stars
- Procedural sound effects (no external audio files needed)
- Pause, restart, and fade transitions

## Project Structure

```
SnakeGame/
├── snakegame          # Main game (single Python file)
├── snake_data.json    # Save file (created on first run)
├── README.md
└── .vscode/
    └── launch.json    # Debug configuration
```

## License

Personal project by arindcha@gmail.com.
