# Tic-Tac-Toe Game

This is a simple Tic-Tac-Toe game built using React. It allows two players to take turns playing as "X" and "O", tracks the history of moves, and can jump to any previous move in the game's history.

## Features

- Two-player turn-based gameplay
- Displays the current player
- Highlights the winner when the game is won
- Allows jumping to any previous move

## Getting Started

These instructions will help you set up and run the Tic-Tac-Toe game on your local machine for development and testing purposes.

### Prerequisites

- [Node.js](https://nodejs.org/en/download/) (which includes npm)

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/tic-tac-toe.git

2. Navigate to the Project Directory:

    ```sh
   cd tic-tac-toe

3. Install the dependencies:
    ```
   npm install

### Running the Game

1.  Start the development server:

    ```
    npm start

2. Open your browser and navigate to http://localhost:3000 to play the game.


## Project Structure

- **Game component** : The main component that manages the game state and history
- **Board component** : Displays the game board and squares.
- **Square component** : Represents a single square on the game board.
- **calculateWinner function** : Determines the winner of the game.

## Components

- **Square** : Renders a button representing a square on the board and handles click events.
- **Board** : Renders the game board with 9 squares and handles the game logic for each move.
- **Game** : Manages the history of moves and allows jumping to previous moves.