# 2048_sliding_game

**Introduction:**
2048 is a single-player sliding tile puzzle game designed by Gabriele Cirulli. The game's objective is to slide numbered tiles on a grid to combine them to create a tile with the number 2048. The game is played on a 4×4 grid, and every time you make a move, a new tile (either 2 or 4) pops up in a random cell. When two tiles with the same number touch, they merge into one with a value equal to the sum of the two tiles.

**Game Mechanics:**
Starting the Game: The game begins with two tiles, which can be either 2 or 4.
Player's Move: Players use keyboard arrows (up, down, left, right) to slide all tiles. When two tiles with the same number touch during a move, they merge into one tile bearing their combined value.
New Tile Appearance: After each turn, a new tile will randomly appear in an empty spot on the board. This tile will be either a 2 (more common) or a 4 (less common).
Game Objective: The game's primary goal is to create a tile with the number 2048. However, players can continue the game to achieve higher scores and larger numbered tiles beyond 2048.
Game Over: The game ends when there are no more moves left to combine tiles or slide them in any direction, and the board is full.
Code Overview:
Functions to Move Tiles: The provided code includes functions (upmove, downmove, leftmove, rightmove) that handle the logic of sliding tiles in the respective direction.
Adding New Tiles: After each move, if there's a change in the board's state, the addblock function randomly inserts a new tile (2 or 4) at an empty position.
Displaying the Board: The disp function displays the current state of the game board.
Checking Board State: The code has check to compare the previous and current states of the board, and checkover to determine if any moves are left or if the game has ended.
Main Game Loop: The main function initializes the game board, displays instructions, handles player input, executes moves, and checks game termination conditions.
How to Play (Based on the Given Code):
Start the game.
Use the keys 'W' (or 'w') to slide up, 'S' (or 's') to slide down, 'A' (or 'a') to slide left, and 'D' (or 'd') to slide right.
The game ends either when the player decides to quit by pressing 'Q' (or 'q') or when no moves are left.
The game's objective is to combine tiles and get to the 2048 tile, but you can continue to play to achieve higher tiles and scores.

