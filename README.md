# Python Game: Dino Runner

## Description
Dino Runner is a simple 2D platformer game created using Pygame, where the player controls a dinosaur that jumps over obstacles while scoring points. The game draws inspiration from the classic Chrome Dino game.
## Controls
- **UP Arrow:** Jump over obstacles.
- **DOWN Arrow:** Duck under obstacles.
- **Any Key:** Restart the game after a game over.

## Features
- **Player Character:** Control a dinosaur that can run, jump, and duck.
- **Obstacles:** Avoid various types of obstacles, including cacti and birds.
- **Scoring System:** Earn points for every frame the dinosaur survives, with increasing speed as points increase.
- **Clouds and Background:** A scrolling background and clouds enhance the visual experience.
- **Restart Mechanism:** Upon collision with an obstacle, the game displays the score and allows the player to restart.

## Installation
1. Install Pygame:
   ```bash
   pip install pygame
Assets/
    Dino/
        DinoRun1.png
        DinoRun2.png
        DinoJump.png
        DinoDuck1.png
        DinoDuck2.png
    Cactus/
        SmallCactus1.png
        SmallCactus2.png
        SmallCactus3.png
        LargeCactus1.png
        LargeCactus2.png
        LargeCactus3.png
    Bird/
        Bird1.png
        Bird2.png
    Other/
        Cloud.png
        Track.png
python your_game_file.py
##Controls
UP Arrow: Jump
DOWN Arrow: Duck
Game Mechanics
The dinosaur starts running automatically.
Press the UP arrow to jump over obstacles.
Press the DOWN arrow to duck under obstacles.
Points are scored for every frame the dinosaur survives, and the game speed increases every 100 points.
Game Over
If the dinosaur collides with an obstacle while not in a jump, the game pauses and shows the player's score. Press any key to restart the game.

Code Structure
Classes:
Dinosaur: Handles the dinosaur's state (running, jumping, ducking) and animations.
Cloud: Manages cloud positioning and movement.
Obstacle: Base class for all obstacles.
SmallCactus, LargeCactus, Bird: Specific types of obstacles.
Functions:
main(): Main game loop that handles game logic and rendering.
menu(): Displays the start/restart menu.
Acknowledgements
This game uses Pygame, a great library for game development in Python. All graphics assets are custom and should be created or sourced properly.

License
This project is open-source. Feel free to modify and use it for personal or educational purposes.

markdown
Copy code

### Notes
- Replace `your_game_file.py` with the actual filename of your game script.
- Customize any sections further if you have additional details to include!
