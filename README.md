# tiktak#
This is a simple console-based Tic Tac Toe game in C#. The game allows two players to play against each other, with Player 1 using 'X' and Player 2 using 'O'. The program features a game loop that continues until there is a winner or a draw. The players take turns choosing a position on the board to place their mark. The game checks for a win, draw, or ongoing game after every turn.

Description of variables and methods:

arr: A character array representing the Tic Tac Toe board. Each element corresponds to a cell on the board.
player: An integer variable to keep track of the current player (1 for Player 1, 2 for Player 2).
choice: An integer variable to store the user's input (1-9) for selecting the desired cell to place their mark.
flag: An integer variable representing the game's status: 0 for ongoing, 1 for a win, and -1 for a draw.
Main methods:

Main: The main method, where the game loop is implemented. It processes user input, updates the game state, and checks for a win or a draw.
Board: This method displays the Tic Tac Toe board in the console, updating the board's appearance after each turn.
CheckWin: This method checks for a win, draw, or ongoing game. It checks for winning conditions horizontally, vertically, and diagonally. If all cells are filled and no winning conditions are met, it returns -1 for a draw. If the game is still ongoing, it returns 0.
To play the game, players take turns entering a number from 1 to 9 representing the cell where they want to place their mark. The game will display the current state of the board, showing the marks placed by both players. The game will continue until there is a winner or a draw, at which point the program will announce the result and terminate.
