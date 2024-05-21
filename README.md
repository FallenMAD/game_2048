# 2048 GAME
  2048 is a puzzle game in which you have to try to combine the tiles and when you get the number 2048, you win this game!
  Please click on the Game 2048 and have a good game!

# [Game 2048](https://FallenMAD.github.io/game_2048/)
# [This game was inspired by original game](https://play2048.co/)

# Game Logic
  - The game field is 4 x 4
  - Each cell can be empty or contain one of the numbers: 2, 4, 8 ... 2^n
  - The player can move cells with keyboard arrows
  - All the numbers should be moved in the selected direction until all empty cells are filled in
      * 2 equal cells should be merged into a doubled number
      * The merged cell can’t be merged twice during one move
  - The move is possible if at least one cell is changed after the move
  - After move 2 or 4 appears in a random empty cell. 4 probability is 10%
  - When 2048 value is displayed in any cell, win message should be shown.
  - The game over message should be shown if there are no more available moves.
  - Hide start message when game starts.
  - Change the Start button to Restart after the first move.
  - Restart button should reset the game to the initial state.
  - Increase score with each move. The score should be increased by the sum of all merged cells.

# Technologies used:
  - HTML
  - Sass (SCSS)
  - Javascript

# For what?
  I created this game because I wanted to improve my JavaScript skills.After practice with more easier tasks, I choose more difficult one to realise all knowledge of JavaScript.Which I have gained so far along, to make this game.

  The main goal of this project was to implement DOM Manipulation and practice with Javascript.
  Also implemented the game logic and combine JavaScript with HTML/CSS.

# How to run it?
  - Copy the link
  - Clone repository ```git clone <repo>```
  - Run ```npm install```
  - Run ```npm start```

# Dependencies
  - Node v14.21.3 or higher
  - npm v6.4.18 or higher

