# IntelliCheckers

## A checkers game written in Java/Swing.

This checkers game is implemented using the Java programming language with the Swing library for creating a graphical user interface (GUI). Swing provides a set of components and tools to build interactive applications, making it suitable for developing the game's user interface.
The game follows the traditional rules of checkers, providing an engaging and challenging experience for players. The graphical interface allows players to easily interact with the game board, select and move their pieces, and track the progress of the game.

## AI implemented using the minimax algorithm and alpha-beta pruning.

The game includes an AI player that utilizes advanced algorithms for intelligent move selection. The AI player is implemented using the minimax algorithm with alpha-beta pruning, a popular technique in game theory and artificial intelligence.
The minimax algorithm is a recursive search algorithm that evaluates all possible moves on the game board and chooses the move that maximizes the AI player's advantage while minimizing the opponent's advantage. By considering multiple levels of moves ahead, the AI player can make strategic decisions and anticipate the consequences of each move.
To further enhance the efficiency of the AI player's decision-making process, alpha-beta pruning is applied. Alpha-beta pruning reduces the number of evaluated moves by eliminating branches of the game tree that are guaranteed to be worse than previously explored moves. This optimization significantly reduces the computational complexity of the algorithm, allowing for faster and more efficient decision-making.
With the implementation of the minimax algorithm and alpha-beta pruning, the AI player in this checkers game demonstrates intelligent gameplay, providing a challenging opponent for human players.

## Game Rules

1. The game is played on a 8x8 checkered board.
2. Each player starts with 12 pieces, which are placed on the dark squares of the board.
3. Players take turns moving their pieces diagonally forward.
4. Regular moves can only be made one square diagonally forward.
5. If a player's piece reaches the opposite end of the board, it becomes a "king" and gains the ability to move and capture in both forward and backward directions.
6. Capturing is mandatory if a player's piece can jump over an opponent's piece.
7. Multiple captures can be made in a single turn if the opportunity arises.
8. The game ends when one player captures all the opponent's pieces or blocks them from making any legal moves.


## Installation

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Go to src/main/Main.java file.
4. Run from "Current File".

## Acknowledgements

This project was inspired by the classic game of checkers and serves as a learning exercise for  implementing SI behavior and basic game mechanics.