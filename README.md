# Tic Tac Toe

Tic Tac Toe is a small web game. Play against the computer or take turns with a friend on the same device. It keeps score across rounds and shows the winning line.

Live demo: https://YOUR-USERNAME.github.io/Tic-Tac-Toe/

Built with: HTML, CSS and JavaScript.

What this project shows: The computer uses an algorithm called minimax. It tries every possible move for both players, scores each ending (win, draw or loss), and picks the move with the best result. Because tic tac toe is small, it can check every game, so the computer never loses. The best a human player can get is a draw. The board is stored as a list of 9 squares, and the win check looks at the 8 possible lines.

What I'm learning from it: I'm studying how the `minimax` function calls itself to look ahead through the game, and how the `winner` function checks the 8 winning lines.
