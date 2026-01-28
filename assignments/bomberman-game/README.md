# 📘 Assignment: Bomberman Game

## 🎯 Objective

Create a simplified version of the classic Bomberman game using Python. You'll practice grid-based game logic, collision detection, and user input handling while building an interactive game experience.

## 📝 Tasks

### 🛠️ Set Up Game Board and Player

#### Description
Create the basic game board structure and initialize the player character with movement controls.

#### Requirements
Completed program should:

- Create a grid-based game board (e.g., 10x10)
- Display the board in the console using text characters
- Initialize a player character at a starting position
- Allow the player to move up, down, left, and right using arrow keys or WASD
- Prevent the player from moving outside the board boundaries


### 🛠️ Implement Bombs and Explosions

#### Description
Add bomb placement and explosion mechanics with a timer system.

#### Requirements
Completed program should:

- Allow the player to place bombs at their current position using a key press
- Display placed bombs on the board
- Implement a countdown timer for each bomb (e.g., 3 seconds)
- Generate explosions when bombs detonate, affecting adjacent cells (up, down, left, right)
- Display explosions visually on the board


### 🛠️ Add Enemies and Game Logic

#### Description
Introduce enemies to the game board and implement collision detection and win/lose conditions.

#### Requirements
Completed program should:

- Spawn enemies on the board that move randomly or follow simple AI patterns
- Display enemies distinctly from the player
- Detect collisions between the player and enemies
- Detect collisions between explosions and enemies (enemies are destroyed)
- Implement a win condition (destroy all enemies) and lose condition (player hit by enemy or explosion)
- Display appropriate game over messages
