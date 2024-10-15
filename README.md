# MazeGame

This project is part of an assignment for my MSc Business Analytics course, where I designed and implemented a mini-game using **Python** and the **medialib** library, based on images provided by the professor. The game applies key programming concepts such as lists, loops, and conditional statements to create an interactive maze experience.

## Project Description

The mini-game challenges players to navigate a maze while avoiding obstacles and collecting points by interacting with different airplane logos. The maze is represented using a list, where each element corresponds to a different type of cell, such as walls, paths, monsters, or airplanes. The player controls an avatar to move through the maze, aiming to collect points and avoid obstacles.

### Key Features

1. **Maze Layout**:
   - The maze is represented by a list of lists, where each element corresponds to a specific type of object in the game (e.g., 'X' for walls, '_' for paths, 'M' for monsters, and airplane logos such as 'B', 'E', 'L', and 'J').
   - The player avatar is initially placed in a predefined position, and the background of the game is drawn using the images from the **MazeGame_imgs** folder.

2. **Player Movement**:
   - Players can control the avatar's movement using the following keys:
     - 'w' to move up
     - 's' to move down
     - 'a' to move left
     - 'd' to move right
     - 'q' to quit the game, displaying a "Game Over!!!" message.
   
3. **Interaction with Airplane Logos**:
   - When the avatar lands on a position with an airplane logo ('E.png', 'J.png', 'L.png'), the airplane image is replaced by the avatar, and a welcome message appears along with 1 point added to the score.
   - For 'B.png' (British Airways), a special interaction occurs where a decision is required from the player (press 'h' or 'i'), which leads to different rewards or outcomes.

4. **Winning Condition**:
   - The game ends when the player accumulates 20 or more points, displaying the **you_win.png** image and terminating the game.

5. **Input Validation**:
   - The game handles invalid inputs and ensures that players can only make valid moves or actions.

## Game Controls

- **w**: Move up
- **s**: Move down
- **a**: Move left
- **d**: Move right
- **q**: Quit the game

## Technologies Used

- **Python**: The game is implemented using Python.
- **Medialib**: A Python library used to manage and display the game images and handle basic game interactions.

## How to Run

Control the avatar using the keys 'w', 'a', 's', 'd' and collect points by interacting with the airplanes. The game will end when you collect 20 points.
