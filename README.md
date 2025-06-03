# 🐍 Snake and Apple Game (with Music & Background)

A modern take on the classic Snake game using Python and Pygame, complete with background music, sound effects, and a custom graphical theme.

---

## 🎮 Game Features

* Control the snake using arrow keys.

* Eat apples to grow longer.

* Background image and looping music for immersion.

* Sound effects for eating and crashing.

* Game-over screen with option to restart.

---

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/4815fb07-11b8-4509-a1d8-56a8307b4955)

![image](https://github.com/user-attachments/assets/8fc2c639-4c09-4239-9fc5-9914cac68ccd)

---

## 🛠️ Requirements

* Python 3.x

* pygame module

* Install Pygame:

```bash
pip install pygame
```

---

## 🗂️ File Structure

```bash
Snake/
├── main.py                           # Main game script
└── resources/
    ├── block.jpg                     # Snake body segment
    ├── apple-removebg-preview.png   # Apple image
    ├── background.jpg               # Background image
    ├── bg_music_1.mp3               # Background music
    ├── ding.mp3                     # Eating sound
    └── crash.mp3                    # Collision sound
```

Ensure that the resources folder is in the Snake/ directory, and that you run the game from the root Snake/ folder.

---

## 🚀 How to Run

Clone or download the repository.

Navigate into the game directory:

```bash
cd Snake
```

Run the game:

```bash
python main.py
```

---

## 🎮 Controls

| Key           | Action                  |
| ------------- | ----------------------- |
| ↑ / ↓ / ← / → | Move the snake          |
| Enter         | Restart after game over |
| Esc           | Quit the game           |

---

## 🎵 Sound System

* Background Music: Plays in a loop.

* Sound Effects:

  * ding.mp3: When the snake eats an apple.

  * crash.mp3: When the snake crashes.

To mute or change the sounds, replace or modify files in the resources/ folder.

---

## ❌ Game Over

* Occurs when the snake:

* Collides with itself.

* Hits the game boundary.

* Displays final score and lets you restart with Enter.

---

## ⚙️ Code Highlights

* Snake class handles movement and growth.

* Apple class handles repositioning and rendering.

* Game class manages game logic, collision detection, UI, and sounds.

* Modular sound system using pygame.mixer.
