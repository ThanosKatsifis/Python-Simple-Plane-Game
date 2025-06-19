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


## 📂 Assets

To ensure everything loads correctly, place the following image files in the **same directory** as your `PlaneGame.py` file (i.e., the root of your project folder):

- jet.png — the player’s airplane  
- missile.png — enemy projectiles  
- cloud.png — scenery  
- 1hearts.png, 2hearts.png, 3hearts.png — heart icons for health display  

Your folder structure should look like this:

```plaintext
/your-project-folder
├── PlaneGame.py
├── jet.png
├── missile.png
├── cloud.png
├── 1hearts.png
├── 2hearts.png
└── 3hearts.png
```

Make sure all images are in the correct format (.png) and appropriately sized for your game screen.

## ▶️ How to Run

From your terminal, run the following command inside the game folder:  
```bash
python PlaneGame.py
```

Ensure your screen resolution is large enough to view the full game window (it's sized to nearly fullscreen minus 100 pixels).

## 🧠 Customization Ideas

- Add sound effects or background music  
- Scale up difficulty as the score increases  
- Introduce power-ups like temporary shields or speed boosts  
- Add player plane skins or enemy types  

## 📃 License

This game is open for learning, customization, and fun! If you modify or reuse it, feel free to credit the original creator. 
