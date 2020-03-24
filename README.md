# tic-tac-toe
A tic tac toe console game written in Python.

## Objectives
1. Learn how to use Git to manage project workflow.
2. Explore how different Python data structures operate.
3. Do something fun that has a simple starting point, but builds in complexity.

## Project Strategy
### Game Board
In tic tac toe, we have a 3x3 board. The minimal functions needed are to draw the board and keep track of the board state. At least for now, I am going to store my board as a list of lists, that looks like this:

[[0, 0, 0],
 [0, 0, 0],
 [0, 0, 0]]

Each list represents a row in the game board. Each space will be assigned an integer corresponding to it's state.
0 - empty
1 - X square
2 - O square

### Player
Issuing player moves is pretty simple. For each player turn, the user will receive a text prompt, and they enter a number 1-9 corresponding to a square in the board as follows:
[1][2][3]
[4][5][6]
[7][8][9]

The program validates each move to satisfy two criteria:
1. The index exists on the board (is a number 1-9)
2. The space indicated is an empty board space.

### Computer
TODO
