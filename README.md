# Tic-Tac-Toe-game

# Explanation:
This code is an implementation of the game of Tic Tac Toe, which allows two players to play the game against each other. The game is played on a 3x3 board where each player takes turns placing their symbol (X or O) on the board. The goal is to get three of your symbols in a row, either horizontally, vertically, or diagonally.

The code uses the minimax algorithm to determine the best move for the AI player (the player playing with the O symbol). The minimax algorithm is a decision-making algorithm that is commonly used in game theory to find the optimal move for a player, assuming that the opponent is also playing optimally.

The functions in the code are as follows:

is_terminal(board) - checks if the game is over by either a player winning or the board being full (in which case it's a draw).

utility(board) - calculates the utility (or value) of a given game state. If X wins, the utility is 1. If O wins, the utility is -1. If it's a draw, the utility is 0.

min_value(board) - a recursive function that is part of the minimax algorithm. It finds the minimum value of all possible moves for the AI player by assuming that the opponent is also playing optimally.

max_value(board) - a recursive function that is part of the minimax algorithm. It finds the maximum value of all possible moves for the human player by assuming that the AI player is also playing optimally.

minmax(board) - finds the best move for the AI player using the minimax algorithm. It tries all possible moves and returns the move that results in the maximum value.

print_board(board) - prints the current state of the board.

main() - the main function that runs the game. It initializes the board and the players, and alternates turns between the two players until the game is over. It also calls the utility function to determine the winner and prints the final result.

# Output:
![AI Assign 2 out 1](https://user-images.githubusercontent.com/92662218/227508938-a172a2c8-337a-44bb-bf15-bdc7eb8f86a7.png)
![AI Assign out 2](https://user-images.githubusercontent.com/92662218/227508954-7a0902b5-e73c-44c5-8dee-e6ae98dd7b91.png)
