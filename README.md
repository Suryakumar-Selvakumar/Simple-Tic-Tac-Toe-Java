# Simple Tic-Tac-Toe

Tic-Tac-Toe is a classic two-player game played on a 3x3 grid where one player is X and the other is O. The
players take turns placing their marks, with X always going first. The player who succeeds in placing three of their
marks in a horizontal, vertical, or diagonal row wins the game.

This project is an interactive Tic-Tac-Toe game in Java, that was built in incremental stages:

1. **Stage 1 - Welcome to the battlefield:**  
   Print a static 3x3 grid filled with X’s and O’s.

2. **Stage 2 - The user is the gamemaster:**  
   Accept a 9-character string from the user representing the grid and display it with proper formatting and borders.

3. **Stage 3 - What’s up on the field?:**  
   Analyze the game state to determine if the game is ongoing, drawn, won by X, won by O, or impossible.

4. **Stage 4 - First move!:**  
   Add interactivity by allowing the user to input coordinates for their move, including input validation for occupied
   cells, out-of-bound coordinates, and invalid input.

5. **Stage 5 - Fight!:**  
   Complete the two-player game loop, alternating between X and O until one player wins or the game ends in a draw.

## Demo

<video width="1920" height="1080" align="center" src=""></video>

## Takeaway

This project significantly strengthened my understanding of 2D arrays, loops, and conditionals in Java. It
also introduced me to more advanced concepts such as state analysis and game logic validation, where I had to
carefully define rules and handle edge cases like impossible states or invalid user input. On top of that, building a
full game loop helped me gain confidence in structuring longer interactive programs that combine user input, validation,
and continuous feedback.