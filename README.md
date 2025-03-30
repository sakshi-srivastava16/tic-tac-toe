# tic-tac-toe
This is a simple command-line Tic-Tac-Toe game written in C++. It supports two players, tracks scores, and allows rematches.

Features:

Two-player mode

Players can enter their names

Keeps track of scores across multiple rounds

Asks who wants to start first

Checks for row, column, and diagonal wins

Detects ties when the board is full

Option for a rematch after each game

How to Play:

Run the program in a C++ environment.

Enter the names of Player 1 (X) and Player 2 (O).

Decide who starts first by entering 1 or 2.

Players take turns selecting a row and column (1-3).

The game announces a winner or a tie when conditions are met.

After each match, the program displays scores and asks if you want a rematch.

Enter 'y' for a rematch or 'n' to end the game.

Example:

Enter name of Player 1 (X): Alice
Enter name of Player 2 (O): Bob
Who will start first (1 or 2)? 1

Alice plays with 'X'
Bob plays with 'O'

  - | - | -  
 ---------
  - | - | -  
 ---------
  - | - | -  

Enter row (1-3): 1
Enter column (1-3): 1

X | - | -
---------
- | - | -
---------
- | - | -

Alice wins!
Score: Alice 1 - 0 Bob
Do you want a rematch? (y/n): y
