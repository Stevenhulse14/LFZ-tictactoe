### TICTACTOE GAME

This is a simple TicTacToe game that can be played by two players. The game is played on a 3x3 grid. The players take turns marking the spaces in the grid with their respective markers (either 'X' or 'O'). The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game.

The game is implemented using Typescript and is just being ran in the terminal.

To run in the terminal make sure that

1. You have ts-node installed on your machine
2. run file `ts-node tictactoe.ts `

## Instructions

1. The game starts with an empty 3x3 grid. AKA the game board.
2. The first player is prompted to make a move by entering the row and column number where they want to place their marker.
3. The second player is then prompted to make a move.
4. The game continues until a player wins or the game ends in a draw.
5. The game ends when a player wins or the game ends in a draw.

## Functions

1. `printBoard()` - This function prints the current state of the game board.
   explore process.stdout.write() and process.stdout.cursorTo() to print the board in a more visually appealing way.

2. `playTurn()` - This function takes in the row and column number where the player wants to place their marker and updates the game board. Using if statements to check if the move is valid and updating the game board accordingly.
3. `checkWin()` - This function checks if a player has won the game. Combining interstin If statements conditions to check for a win.
4. `switchPlayer()` - This function switches the current player. creating a way to switch between players.
5. `promptPlayer()` - This function prompts the current player to make a move. Prompt the player to enter a row and column number. based on this input, the `playTurn()` function is called. `printBoard()` is also called to print the updated game board. and another `promptPlayer` is called to prompt the next player to make a move.
6. `checkDraw()` - This function checks if the game has ended in a draw.
