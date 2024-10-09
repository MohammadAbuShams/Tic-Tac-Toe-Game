# Tic-Tac-Toe Game

This is a simple and interactive Tic-Tac-Toe game built using HTML, CSS, and JavaScript. The game allows two players to alternate turns, placing "X" and "O" on a 3x3 grid. The game checks for a win, draw, and also allows for a quick reset to play again.

### Play the Game Live:
You can play the game directly here: [Tic-Tac-Toe Game](https://mohammadabushams.github.io/Tic-Tac-Toe-Game/)

## Features
- Interactive 3x3 Tic-Tac-Toe grid.
- Two-player mode.
- Displays the current turn with "X" and "O".
- Win detection and draw detection.
- Restart functionality to play multiple games.

## Technology Stack
- **HTML**: Provides the structure of the game board.
- **CSS**: Adds styling to make the game look clean and responsive.
- **JavaScript**: Handles game logic, user input, and win/draw detection.

## Game Logic
- **Player Turns**: The game alternates turns between two players. Player 1 is "X" and Player 2 is "O".
- **Win Detection**: The game detects when a player wins by checking if there are three matching symbols in a row, column, or diagonal.
- **Draw Detection**: If all cells are filled and there is no winner, the game declares a draw.
- **Restart**: After each game, you can click the "Restart Game" button to play again.

## Files Overview

### `index.html`
This file contains the basic structure of the game, including the 3x3 grid and buttons.

### `style.css`
This file provides the styling for the game, ensuring that the layout looks neat and the X/O symbols are clearly visible.

### `script.js`
This file handles the game logic:
- Alternates turns between players.
- Checks for a win or draw.
- Updates the grid with the current player's symbol.
- Restarts the game.


