# Project0
## A tic-tac-toe game 

![A game screen shot](https://github.com/MrMaverick79/MrMaverick79.github.io/blob/main/images/TTT-screenshot.png)

----

Author: Brendan Tuckerman

Link: https://mrmaverick79.github.io/project0/

Background / Spec:  

A tic-tac-toe game using HTML, CSS, JavaScript and Jquery.

<<<<<<< HEAD
Implements a minimax algorithm for the 'impossible ai'.

This is the first project as part of General Assembly's Software Engineering Intensive 2022. 
=======
Implements a minimax algorithm for the 'impossible ai'

This is the first project as part of General Assembly's Software Engineering Intensive. 
>>>>>>> 8036f241052632e1e830b30e755945ef5da90345

### Technical Requirements

Your app must:

- Render a game board in the browser
- Switch turns between X and O (or whichever markers you select); your game should prevent users from playing a turn into a square that is already occupied
- Visually display which side won if a player gets three in a row; or show a draw/"cat’s game" if neither wins
- Include separate HTML / CSS / JavaScript files
- Stick with KISS (Keep It Simple Stupid) and DRY (Don't Repeat Yourself) principles
- Use Javascript with jQuery (or vanilla DOM methods if you really prefer) for DOM manipulation
- Deploy your game online, where the rest of the world can access it
- Use semantic markup for HTML and CSS (adhere to best practices)

## Features

AI:
- Easy (AI randomly selects a square)
- Medium (AI chooses random 50% of the time, impossible 50% of the time)
- Impossible (AI determines all possible future moves and gives them a score of either +10 or -10, dependent on the outcome. The then determine the move with th highest score.)

UI:
- Tracks Player wins and Computer wins
- Lightweight interface


### TODO

 - AI (~~simple: random~~, ~~intermediate, random 50%, impossible 50%~~, ~~impossible: minmax~~)
 - ~~Restart button~~
 - ~~media queries~~
 - ~~move script tags to the bottom as does not run 50% of the time.~~
 - ~~Turn display is not toggling~~
 - DRY code
 - ~~Remove console.logs~~
 - ~~Add 'menu' which shows win / loss / draw + allows you to select Easy / Medium / Impossible~~
 - ~~Player wins is being replaced with showturn()~~
 - Choosing a game difficulty needs to reset the board
 

 ### Log

 Day 1: 

 - Created game logic for 3 x 3 game in JS.
 - Styled page and linked game logic to html using JQuery.

 Day 2:

- Created a reset button and reset functionality.
- updated styling in side panel
- created basic (random) AI player
- read up on Minmax ai algorithm for the 'impossible' AI

Day 3:

- Refactored code to use only array to store data
- Multiple refactors to make code succinct
- Fixed display toggle
- Created impossible AI using min max
- created underline styles for menu items.
- dealt with edge cases and bugs around clicking the same squares

Day 4:

- Added more detailed explanation of code in the comments.
- Updated the READ.ME and documentation.

## Known bugs / Future fixes / Wish list


** Bugs **
- Media queries for small screens misaligned
- Clicks still available post game

** Future Fixes **
- Game log on right hand side showing moves
- Update README for formatting
- Update README to explain the impossible AI
- Human / AI toggle
- Remove hardcoded win states
