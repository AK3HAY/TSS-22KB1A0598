**Name:** M. Akshay  

**Company:** Tech Sign Solutions

**Duration:** 19 August to 06 September 2024  

**Mentor:** Satya and Anvesh

**Tic Tac Toe Game**
=====================

**Overview**
-----------

This is a simple implementation of the classic Tic Tac Toe game built using HTML, CSS, and JavaScript.

**Gameplay**
---------

The game is played on a 3x3 grid, where two players, X and O, take turns marking a square. The first player to get three of their marks in a row (horizontally, vertically, or diagonally) wins the game. If all squares are filled and no player has won, the game is a draw.

**Technical Details**
-------------------

### HTML

* The game board is represented as a 3x3 table in `index.html`.
* Each table cell contains a `<div>` element that displays the player's mark (X or O).

### CSS

* The game board is styled using `styles.css`, which includes basic layout and design elements.
* The CSS file also includes hover effects and animations to enhance the user experience.

### JavaScript

* The game logic is implemented in `script.js`, which includes functions to:
	+ Handle player moves (update the game board and check for wins)
	+ Check for wins and draws
	+ Reset the game board
	+ Update the game state (whose turn it is, etc.)

**How to Play**
--------------

1. Open `index.html` in a web browser to start the game.
2. Players take turns clicking on empty squares to place their marks (X or O).
3. The game will automatically check for wins and draws after each move.
4. To reset the game, click the "Reset" button.

**Known Issues**
--------------

* None currently known. If you encounter any issues, please report them to the developer.

**License**
---------

This game is licensed under the MIT License. See `LICENSE` for details.

