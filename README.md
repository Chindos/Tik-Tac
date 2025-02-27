This is a simple implementation of the Tic Tac Toe game in C.

Description
The program implements a Tic Tac Toe game for two players. The game is played in the console, where players take turns entering the row and column numbers (from 1 to 3) to place their symbol (X or O) on the board. The game ends when one of the players wins or when all cells are filled, resulting in a draw.

Compilation
To compile the program using GCC, run:

bash
Copy
gcc tictactoe.c -o tictactoe
Note: Ensure that the source file is named tictactoe.c.

Usage
To run the program, execute:

bash
Copy
./tictactoe
When the program starts, it displays the game board and prompts the current player for their move. If invalid coordinates are entered or the selected cell is already occupied, the program will ask for input again.

Sample Game
sql
Copy
   |   |   
---+---+---
   |   |   
---+---+---
   |   |   

Player X, enter row and column (1-3): 1 1

 X |   |   
---+---+---
   |   |   
---+---+---
   |   |   

Player O, enter row and column (1-3): 1 2
