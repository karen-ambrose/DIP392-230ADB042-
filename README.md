# DIP392-230ADB042-
This document provides an overview of the Connect 4 game implementation and instructions for interacting with the system.
[My Report](https://docs.google.com/document/d/1Poxk5WHX8FeAfce0KaPa8Dty3baEi1V-/edit?usp=sharing&ouid=100321223622549804798&rtpof=true&sd=true)
Connect 4 Game Overview:
Connect 4 is a two-player game played on a 6x7 grid. The objective is to be the first player to connect four of their own pieces in a horizontal, vertical, or diagonal line on the game board.

Implementation Details:
The Connect 4 game is implemented in C++. The game utilizes the following programming concepts:
Requirements gathering: The first step is to gather and define the requirements for the Connect 4 game. This involves understanding the desired functionality, user interactions, and any specific features or constraints. Clear requirements help guide the development process and ensure that the final implementation meets the intended goals.
Design and architecture: Before writing code, it's important to plan the overall design and architecture of the Connect 4 game. This includes deciding on the structure of the code, the organization of functions or classes, and the relationships between different components. A well-designed architecture promotes modularity, extensibility, and maintainability of the codebase.
Data structures: I'll need to represent the game board and track the state of each cell. One common approach is to use a two-dimensional array or a matrix to represent the game board. Each cell can be represented by a value, such as '|_|' for an empty cell, 'X' for player 1's piece, and 'O' for player 2's piece.
Loops and conditionals: I'll use loops and conditionals to iterate through the game board, check for win conditions, validate user inputs, and handle game flow. For example, I'll use loops to check for four consecutive pieces in a row, column, or diagonal, and conditionals to determine if a move is valid or if a player has won.

Instructions for Interacting with the System:

Prerequisites:
C++ must be installed on your system.

Clone the Repository:
Clone the Connect 4 game repository to your local machine.

Build and Run the Game:
Navigate to the project directory.
Compile and build the game.
Run the game.

Game Flow:
The game will display an empty game board.
Player 1 is represented by "X" and Player 2 is represented by "O".
Each player takes turns entering the column number (1-7) where they want to drop their piece.
The game board is updated accordingly, and after each move, the updated board is displayed.
The game continues until a player wins or the game board is completely filled.

End of Game:
If a player connects four of their own pieces, the game will display a win message terminates.
If the game board is completely filled without a winner, the game ends in a draw.
Additional Notes:
Error handling is implemented to validate user inputs and handle invalid moves gracefully.
The game can be extended to include additional features, such as an AI opponent or a graphical user interface (GUI), based on the desired requirements.
Make sure to test the game thoroughly, including different win conditions and edge cases, to ensure its correctness.
Please refer to the documentation and inline comments in the code for further details on the implementation and customization options.
