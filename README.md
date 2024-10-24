This project is a classic Snake Game implemented in C++. It is a console-based game where you control a snake to collect fruits. The snake grows longer each time it consumes a fruit, making the game progressively more challenging. The goal is to score as many points as possible by eating fruits while avoiding collisions with the snake's own body.

Features
Fruit Collection: Collect fruits to grow the snake and increase your score.
Smooth Movement: Navigate the snake through the game grid using keyboard controls.
Borderless World: The snake can move through the edges of the grid and reappear on the opposite side.
Self-Collision Detection: The game ends if the snake collides with itself.
Score Display: The current score is displayed on the screen.

Game Controls
W: Move Up
A: Move Left
S: Move Down
D: Move Right
X: Exit Game

Dependencies
Windows Libraries: This project uses conio.h for keyboard input and windows.h for controlling the game speed with Sleep(). These libraries are specific to Windows, so the game may not run on other platforms without modification.
