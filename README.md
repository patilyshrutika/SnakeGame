Snake Game Using Python (pygame)
- Overview

This repository contains a simple Snake game implemented using Python and the pygame library.
The code demonstrates basic game development concepts such as movement, collision detection, score tracking, and event handling.

- Technologies Used

Python 3

pygame

Git and GitHub

- Repository Structure
SnakeGame/
│
├── snake_game.py     # Main game file
└── README.md         # Documentation

- Game Description

The snake is controlled using the keyboard arrow keys

Food appears randomly on the screen

Each time the snake eats food, its length increases

The game ends if the snake collides with the wall or itself

The current score is displayed during gameplay

- Game Features

Orange background

Green snake body

Red food block

Real-time score display

Smooth keyboard-controlled movement

- How to Run
Step 1: Install pygame
python -m pip install pygame

Step 2: Run the game
python snake_game.py

- Controls
Key	Action
Left Arrow	Move left
Right Arrow	Move right
Up Arrow	Move up
Down Arrow	Move down

- Concepts Demonstrated

Game loop implementation

Keyboard input handling

Collision detection

Random placement of objects

Score tracking

Basic 2D graphics using pygame

- Notes

The game uses grid-based movement for consistent behavior

Snake movement is based on fixed step sizes

The code can be extended with additional features

