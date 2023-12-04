# Game Center

This C program presents a Game Center console application that includes two classic games: Tic Tac Toe and Rock-Paper-Scissors. The user can select their preferred game to play from a simple menu.

## Getting Started

To run the Game Center program, follow these steps:

copy the raw code and use Dev c++ compiler to run my code.

## Algorithm
Tic Tac Toe Algorithm
Initialize the Tic Tac Toe board:

Create a 3x3 grid to represent the board.
Initialize each cell with an empty space (' ').
Draw the Tic Tac Toe board:

Display the current state of the board with rows and columns labeled.
Check for a winner:

Check rows and columns for a winning pattern (three consecutive marks of the same player).
Check diagonals for a winning pattern.
If any pattern is found, declare the player as the winner.
Make a move:

Prompt the current player to input the row and column to place their mark.
Validate the input for a valid move:
Ensure the cell is within the board boundaries.
Ensure the selected cell is empty.
Place the player's mark on the selected cell.
Switch players:

Alternate between 'X' and 'O' marks for each player's turn.
Continue until a player wins or the board is filled (draw).
End of the game:

Display the final board state.
Declare the winner or announce a draw.
Rock-Paper-Scissors Algorithm
Display game introduction:

Print the instructions for Rock-Paper-Scissors.
Prompt the player to choose a move (rock, paper, or scissors).
Generate computer's move:

Use a random number generator to select a move for the computer.
Compare moves:

Determine the winner based on the choices:
Rock crushes scissors.
Scissors cut paper.
Paper covers rock.
Display results:

Show the player's and computer's moves.
Declare the winner or announce a tie if both chose the same move.
Repeat or quit:

Ask the player if they want to play again.
If yes, repeat steps 1 to 4; if not, end the game.
