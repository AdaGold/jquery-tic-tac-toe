# Tic Tac Toe!
Create a JavaScript class that, when instantiated, draws a playable tic-tac-toe game in your browser!

## Getting Started
- Create a class using a `function` definition and a `prototype` object.
- Use [jQuery](https://jquery.com/) to enable & manage interactions in the `DOM`.
- Use one markup file, one stylesheet, and one JavaScript file for your solution.

## Rules & Specs
- The game is played on a 3x3 grid.
- Each player, in turn, selects one available grid spot
- Upon selecting (clicking), the spot is marked as belonging to that player
- If a player claims three spots in a row (horizontally, vertically, or diagonally), they win!
- It is possible (even likely) that games can end in a draw.

## Added fun!
- Add a single player mode where, after taking your turn, the computer (JavaScript)...
    + Selects the first available spot OR
    + Randomly selects a spot OR
    + Picks the "best" spot (whatever best means)
- Add a _new game_ button that resets the board, allowing a fresh game to be played.
- Keep track of wins and losses for both players, updating the counts whenever a game ends.
