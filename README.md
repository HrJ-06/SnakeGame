# Snake Game in C++

This is a simple console-based Snake game implemented in C++. The game utilizes the Windows console for display and input handling.

## Features

- **Snake Movement**: Control the snake's direction using W (up), A (left), S (down), and D (right) keys.
- **Food Generation**: Randomly spawns food ('o') on the screen for the snake to eat.
- **Score Tracking**: Keeps track of the score based on the number of food items eaten.
- **Game Over**: Ends when the snake collides with itself or the screen boundaries.

## Dependencies

- **Windows.h**: Used for console manipulation (`gotoxy()` and `SetConsoleCursorPosition()`).
- **conio.h**: Provides console input functions (`kbhit()` and `getch()`).
- **stdlib.h**, **time.h**: Standard libraries for random number generation (`rand()`, `srand()`) and timing (`Sleep()`).
