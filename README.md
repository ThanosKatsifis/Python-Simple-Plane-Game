# Python-Simple-Plane-Game
This code is a begginers python game . For the complete install read the README file :)

# ✈️ Plane Game

A simple yet addictive 2D airplane game built with Pygame! Navigate your jet through clouds and avoid incoming rockets while trying to survive as long as possible and rack up your score. Watch out—collisions will cost you hearts!

## 🚀 Gameplay Features

- Jet-controlled player movement (WASD / Arrow keys)
- Randomly spawning enemy rockets and clouds
- Heart-based health system
- Real-time score updates every 10 seconds
- Game over screen with final score display
- Cloud overlays for visual effect

## 🎮 Controls

| Key         | Action                |
|-------------|------------------------|
| W / Up      | Move Up               |
| S / Down    | Move Down             |
| A / Left    | Move Left             |
| D / Right   | Move Right            |
| ESC         | Quit the game         |

## 💻 Requirements

- Python 3.x
- [Pygame](https://www.pygame.org/)

You can install pygame with:

```bash
pip install pygame

📂 Assets
Make sure the following images are placed in your project directory:

jet.png — the player’s airplane

missile.png — enemy projectiles

cloud.png — scenery

1hearts.png, 2hearts.png, 3hearts.png — heart icons for health display

▶️ How to Run
Simply run: python PlaneGame.py

To ensure everything loads correctly, place the following image files in the same directory as your PlaneGame.py file (i.e., the root of your project folder):
/your-project-folder
│
├── PlaneGame.py
├── jet.png
├── missile.png
├── cloud.png
├── 1hearts.png
├── 2hearts.png
└── 3hearts.png

📸 Asset Descriptions
jet.png: The image of the player-controlled jet

missile.png: The image representing enemy rockets

cloud.png: Decorative cloud sprites that create depth and visual interest

1hearts.png, 2hearts.png, 3hearts.png: Health indicator icons showing remaining hearts

Make sure all images are in the correct format (.png) and are appropriately sized. The game dynamically scales certain assets like missiles, but having optimized sizes beforehand improves performance.

🧠 Customization Ideas
Add sound effects and music for collisions and movement

Introduce difficulty scaling based on score

Add collectibles or power-ups

Include more plane models or skins

📃 License
Feel free to adapt and expand this project for learning or personal fun. Please give credit if reused or modified!

Have fun flying! 🚁
