# Tic Tac Toe
**Welcome to the Tic Tac Toe game implemented in Python! This project is a simple command-line version of the classic Tic Tac Toe game. It allows two players to play against each other in a 3x3 grid until one of the players wins or the game results in a tie.**

## Table of Contents
- **Introduction**
- **How to Play**
- **Features**
- **Code Structure**
- **Running the Game**

## Introduction
- **Tic Tac Toe is a game for two players, usually X and O, who take turns marking the spaces in a 3×3 grid. The player who places three of their marks in a horizontal, vertical, or diagonal row wins the game. If all nine squares are filled and neither player has three marks in a row, the game is a tie.**

# How to Play:
- ### Player Symbols: At the start, Player 1 chooses their symbol (X or O). Player 2 automatically gets the other symbol.
- ### Taking Turns: Players take turns to pick a row and a column to place their symbol.
- ### Winning the Game: The first player to align three of their symbols horizontally, vertically, or diagonally wins the game.
- ### Tie Game: If all the spaces are filled and no player has aligned three symbols, the game ends in a tie.
## Features:
- **Interactive Gameplay:** The game prompts players to make their moves and provides feedback on invalid moves (out-of-range or already filled squares).
- **Automated Win Check:** The game automatically checks for a win after each move.
- **Tie Detection:** The game checks for a tie when the board is full.
- **Game Summary:** After the game ends, a summary is provided with the winner or a tie message.
# Code Structure:
- **main(): The entry point of the game. It initializes the board, gets player symbols, and starts the game.**
- **intro(): Introduces the game and displays the rules.**
- **create_grid(): Creates and returns an empty 3x3 game board.**
- **sym(): Assigns symbols to the players.**
- **startGamming(): Manages player turns, checks for valid moves, and updates the board.**
- **isFull(): Manages the game loop, checks if the board is full, and calls the win detection function.**
- **outOfBoard(): Handles out-of-range move selections.**
- **printPretty(): Displays the game board in a user-friendly format.**
- **isWinner(): Checks for a winning combination on the board.**
- **illegal(): Handles already-filled square selections.**
- **report(): Provides a summary of the game.**
## Running the Game:
- **To run the game, follow these steps:**

- Ensure you have Python installed on your machine.

- Download the source code.

- Open a terminal and navigate to the directory containing the source code.

- **Run the command:**
<a href="">python tictactoe.py</a>
