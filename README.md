# Tic Tac Toe Game

This is a simple **Tic Tac Toe** game built using Python's `tkinter` library for the graphical user interface. It allows two players to take turns and play the classic game of Tic Tac Toe on a 3x3 grid.

## Features

- **Two-player Gameplay**: Players alternate turns, marking their symbol (`X` or `O`) on the board.
- **Winner Detection**: The game automatically detects horizontal, vertical, and diagonal wins.
- **Tie Detection**: Declares a tie if the grid is full and no player has won.
- **Restart Game**: A restart button lets players start a new game without restarting the application.
- **User-friendly Interface**: The game uses colors and styles to make it visually appealing and easy to use.

## Requirements

- Python 3.x
- `tkinter` library (comes pre-installed with Python on most systems)

## How to Run

1. Ensure Python 3.x is installed on your system.
2. Copy the code into a `.py` file (e.g., `tic_tac_toe.py`).
3. Run the script using the following command:
   ```bash
   python tic_tac_toe.py
4. A game window will appear where two players can play Tic Tac Toe.

## Controls

- **Gameplay**: Click on any empty grid cell to place your symbol (`X` or `O`).
- **Restart**: Click the **restart** button at the bottom of the window to start a new game.

## Game Rules

1. The game starts with Player `X` taking the first turn.
2. Players take turns clicking on an empty cell to mark it with their symbol (`X` or `O`).
3. The first player to get three of their symbols in a row, column, or diagonal wins.
4. If all nine cells are filled and no player has won, the game ends in a tie.

## Code Highlights

- **Dynamic Grid Creation**: The game board is dynamically generated using `tkinter` buttons in a 3x3 layout.
- **Winner and Tie Detection**: The `check_winner` function determines the game's result after every move.
- **Reset Functionality**: The `new_game` function clears the board and resets the game state.

## Customization

- **Colors**: The game colors are defined in the code and can be adjusted by modifying these variables:
  - `color_blue`: Player text color.
  - `color_yellow`: Winner text and highlight color.
  - `color_gray`: Background color.
  - `color_light_gray`: Winning combination highlight.
- **Fonts**: The font family and size for buttons and labels can be changed in the `font` parameter in the `tkinter` widget initialization.

## Enjoy Playing!

Have fun playing the classic Tic Tac Toe game!





