# Tic Tac Toe Game

Welcome to the Tic Tac Toe game built with Python and Tkinter! This classic game allows two players to compete against each other by placing their marks (X or O) on a 3x3 grid, with the goal of getting three of their marks in a row, either horizontally, vertically, or diagonally.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Code Explanation](#code-explanation)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features

- **Two-Player Mode**: Play against a friend or family member.
- **Interactive GUI**: Simple and user-friendly interface using Tkinter.
- **Automatic Winner Detection**: The game checks for a winner or a tie after each turn.
- **Restart Option**: Easily restart the game with the click of a button.

## Installation

To run this game, you need to have Python installed on your machine. You can download Python from [python.org](https://www.python.org/downloads/).

### Clone the Repository

1. Clone this repository using the following command:
   ```bash
   git clone https://github.com/bellamh/tictactoe.git
   ```
2. Navigate to the project directory:
   ```bash
   cd tictactoe
   ```

### Run the Game

Ensure you have Tkinter installed (it comes pre-installed with most Python distributions). To run the game, use the following command:
```bash
python tictactoe.py
```

## How to Play

1. Launch the game by running the `tictactoe.py` script.
2. The game window will display a 3x3 grid.
3. Player X goes first; click on any empty square to place your mark.
4. Players take turns placing their marks on the board.
5. The game announces the winner or declares a tie when applicable.
6. Click the **Restart** button to play again without restarting the application.

## Code Explanation

This project is structured using functions to handle different parts of the game:

- **Setting Tiles**: 
  - The `set_tile(row, column)` function updates the game board based on player input and switches between players.

- **Winner Check**:
  - The `check_winner()` function checks for winning combinations after each move (rows, columns, and diagonals).

- **Game Reset**:
  - The `new_game()` function resets the board for a fresh start.

- **User Interface**:
  - The GUI is created using Tkinter, which includes buttons for each cell in the grid and labels for displaying the current player and game status.

### Colors Used

- **Blue**: `#4584b6` - The color of the marks and the buttons.
- **Yellow**: `#ffde57` - Used to indicate the winner and for tie messages.
- **Gray**: `#343434` - The background color of the game board.
- **Light Gray**: `#646464` - The background color of winning marks.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- Special thanks to the open-source community for providing valuable resources and libraries that made this project possible.
- Inspiration from classic games and the desire to enhance my programming skills with Python and GUI development.

---

Thank you for checking out my Tic Tac Toe game! Feel free to contribute, report issues, or suggest improvements.
