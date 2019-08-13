# KnightsTour

This project handles the chessboard knight's tour problem.

Project tech spec: Web client technologies (html, css, javascript).

Project files: 

1. Css: index.css.
2. Js:

* tour.js - The backend of the project. Contains main "tour" function that receives x and y (as starting position) and the chessboard size. 
The function will return an array that includes the knight moves and the path for each move.

* helper.js - Contains helper methods which handles all kind of functional stuff such as chessboard initialization, creating a chessboard copy and an indication whether the knight's tour is completed.

* draw.js - handles client issues - such as dynamically drawing the chessboard or moving the knight between positions.

3. HTML:

* index.html (Completed) - 2 input fields which receives "X" and "Y" as the knight starting position and a button which starts the tour.
Tour GUI explanation: The knight is jumping between positions (these moves are represented as "NextMove").
Tracking - Red dot img which tracks the path of the knight to the "NextMove" position.
Current path - Green dot img which shows each step the the knight will do in order reach the "NextMove".

* IndexWithSvg.html (Not completed) - Basically the same as index.html but with SVG line and not dots. currently there is a problem with "X" and "Y" coordinates relatively to the board.

Note: Chessboard movements are dealayed with 800 milliseconds. 










