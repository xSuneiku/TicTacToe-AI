# Tic-Tac-Toe with AI Opponent

The Python code implemented in tictactoe.py outlines the logic for a Tic-Tac-Toe game, it also uses the
Minimax algorithm to run the AI who will play against you optimally. I created a game of Tic-Tac-Toe
against an AI that is played with a graphical user interface (GUI) using the Pygame library.
The core of the AI, the minimax function, decides the optimal move for the AI by evaluating all possible
future game states and selecting the move that maximizes the AI's chance of winning while minimizing
the opponent's chance.
I ran some tests against the AI in a series of games. My documentation focused on the performance
differences when the user plays as 'X' (user first) versus when playing as 'O' (AI first). The following is
my findings:
• When I choose to play as 'X' (player goes first), all 6 of the games I played against the AI resulted
in a tie, this was me playing optimally. This shows the Minimax algorithm's effectiveness in
making sure that the AI can secure a draw at minimum, given optimal play by both sides.
• On the other hand, when I choose to play as 'O' (AI goes first), the outcome of 4 games was 2 ties
and 2 losses. This showed me that playing as 'O' presents more of a challenge due to 'X' having
the first move advantage, in the end optimal play could still not lead to a favorable outcome
against the AI.

## Project Overview
This project implements a game of Tic-Tac-Toe with a graphical user interface (GUI) by using Python and the Pygame library. The user will play against an AI who plays optimally using the Minimax algorithm.

### Prerequisites
- Version of Python 3.x
- Pygame (library)

### Setup
1. Make sure to have Python 3.x installed on your system.
2. You can install Pygame by running `pip3 install pygame` in the terminal of "runner.py".

### Running the Game
1. Navigate to the terminal of "runner.py" and run the game using the command `python runner.py`.
2. The game window should open, allowing you to play Tic-Tac-Toe against the AI.
3. Choosing "X" will let you (the player) go first, choosing "O" will let the AI go first.
