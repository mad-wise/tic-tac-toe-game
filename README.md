# React Tic-Tac-Toe Game

This repository contains a React-based implementation of the classic Tic-Tac-Toe game. The game is built with a focus on modern React practices, including the use of functional components and hooks.

## Features
- **Dynamic Player Names**: Players can set and update their names dynamically.
- **Game Log**: Keeps track of all the moves made during the game.
- **Winning Logic**: Includes logic to determine the winner based on pre-defined winning combinations.
- **Game Board**: Interactive game board where players can click to make their move.
- **Game Over Component**: Displays the winner and provides an option to restart the game.

## Installation
To get started with this project, clone the repository and install the dependencies:
```bash
git clone https://github.com/your-username/react-tic-tac-toe.git
cd react-tic-tac-toe
npm install
````

## Running the Application
Start the application by running:
```bash
npm run dev
````
This will launch the game in your default web browser.

## How to Play
- **Set Player Names**: Optionally set the names of the players.
- **Making Moves**: Click on the empty squares to make a move. The game alternates turns between Player 1 (X) and Player 2 (O).
- **Track Game Progress**: The game log updates with each move, showing the history of turns.
- **Identify Winner**: The game identifies and announces a winner once one of the winning combinations is achieved.
- **Restart the Game**: Use the restart button to reset the game board and start a new game.

## Components
- **Player**: Component to display and update player names.
- **GameBoard**: Interactive grid where the game is played.
- **Log**: Component to display the history of moves.
- **GameOver**: Displays the game's outcome and a restart button.
