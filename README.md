**Tic-Tac-Toe Game**
Welcome to the Tic-Tac-Toe game! This is a simple implementation of the classic game using HTML, CSS, and JavaScript. It allows two players to take turns marking spaces on a 3x3 grid and determines the winner based on predefined winning patterns.

**Features**
Turn-Based Gameplay: Players take turns placing their markers ("O" or "X") on the board.
Win Detection: The game checks for a winner after every move and displays a congratulatory message.
Reset Functionality: A reset button allows players to start a new game at any time.
Table of Contents
Getting Started
How to Play
Code Overview
Contributing
License
Getting Started
To get started with this Tic-Tac-Toe game, you need to have a basic understanding of HTML, CSS, and JavaScript. Follow these steps to run the game locally:

**Clone the Repository:**

bash
Copy code
git clone <repository-url>
cd tic-tac-toe
Open the HTML File:

Open index.html in your web browser to play the game.

**How to Play**
Start the Game:

The game begins with "O" as the starting player. Click on any empty cell to place your marker.
Alternate Turns:

The game alternates turns between "O" and "X". Each player takes turns clicking on an empty cell to place their marker.
Winning the Game:

The game will automatically detect a winner based on predefined winning patterns:
Three markers in a row (horizontal, vertical, or diagonal).
A message will be displayed declaring the winner once a winning pattern is found.
Resetting the Game:

Click the "New Game" button to reset the game board and start over.
Code Overview
Here is a brief overview of the main components of the game:

**HTML Structure:**

The game board consists of nine clickable boxes arranged in a 3x3 grid.
Buttons for resetting the game and displaying messages.
JavaScript Logic:

boxes: An array of game cells.
resetBtn: The button used to reset the game.
msgContainer: Container for displaying game messages.
msg: Element to show the winner message.
PlayAgain: Button to start a new game.
turnO: Boolean to track whose turn it is.
winPatterns: Array defining the winning combinations.

**Functions:**
showWinner(winner): Displays the winner and hides the game board.
checkWinner(): Checks the current board for a winning pattern.
disabledBtn(): Disables all boxes to prevent further moves.
enableBtn(): Enables all boxes and clears their content.
resetGame(): Resets the game state and board for a new game.
