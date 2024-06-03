# Tic-Tac-Toe-Game
<h2>Deplolyed App: https://saviour-figma-project.vercel.app/</h2>  


This is a simple Tic Tac Toe game implemented using React and Chakra UI. The game includes background music that plays continuously and a "ting" sound effect that plays whenever a player makes a move.

Features
Tic Tac Toe Gameplay: Classic 3x3 grid where two players take turns to mark X and O.
Sound Effects:
Background Music: Continuous background music that starts when the game begins.
Move Sound: A "ting" sound effect that plays each time a player clicks on a square.
Winner Announcement: Displays the winner or announces a draw at the end of the game.
Reset Game: Allows players to reset the game and start over.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/tic-tac-toe-game.git
cd tic-tac-toe-game
Install dependencies:

bash
Copy code
npm install
Run the application:

bash
Copy code
npm start
Usage
Start the Game: Click the "Start Game" button to begin.

This will start the background music.
Play the Game: Click on any square to place your mark (X or O).

A "ting" sound will play with each move.
Game Outcome:

The winner will be announced once three of the same marks are in a row (horizontal, vertical, or diagonal).
If all squares are filled without a winner, the game will announce a draw.
Reset the Game: Click the "Reset Game" button to clear the board and start a new game.

Technical Details
React: A JavaScript library for building user interfaces.
Chakra UI: A simple, modular, and accessible component library that gives you all the building blocks you need to build your React applications.
Audio Handling: Utilizes HTML5 Audio elements for background music and sound effects.
Implementation Notes
Background Music:

The background music (music.mp3) starts playing when the user clicks the "Start Game" button to comply with modern browser autoplay restrictions.
The music is set to loop continuously.
Move Sound Effect:

The "ting" sound (ting.mp3) is played every time a player makes a move by clicking on a square.
State Management:

The game state, including the board, current player, and winner, is managed using React hooks (useState, useEffect).
A useRef hook is used to manage the audio elements.
