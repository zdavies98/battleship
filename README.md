# Battleship Game

## Overview

This project is a recreation of the classic board game Battleship using JavaScript. It features a simple user interface and implements the core mechanics of the game, including placing ships, taking turns to attack, and determining the winner.

## Features

- Player vs. Computer mode
- Randomized ship placement for the computer
- Interactive grid for placing ships and taking shots
- Game status updates (hit, miss, sunk, win)

## Getting Started

### Prerequisites

To run this project, you need a modern web browser (e.g., Chrome, Firefox, Safari).

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/zdavies98/battleship.git
    ```

2. Open the `index.html` file in your web browser to start the game.

## Project Structure

The project structure is as follows:

```
battleship/
├── styles.css
├── app.js
├── index.html
└── README.md
```

## Components

### `index.html`

The main HTML file that sets up the basic structure of the webpage and includes references to CSS and JavaScript files.

### `styles.css`

Contains the styling for the game, including the layout of the game board and the appearance of the ships and hits/misses.

### `app.js`

The main JavaScript file that handles all functionality including: 
- Initializes the game, handles user interactions, and updates the game state
- Defines the game board, including functions for placing ships, checking for hits/misses, and tracking the state of each cell
- Defines the ship objects, including properties such as size, coordinates, and hit status
- Contains utility functions used throughout the project, such as generating random coordinates and checking for valid ship placement

## How to Play

1. **Place Your Ships:**
   - Click on a cell to place a ship. Ships can be rotated by clicking the flip buttonn.
   - Place all ships on the grid before starting the game.

2. **Start the Game:**
   - Once all ships are placed, click the "Start Game" button to begin.

3. **Take Turns:**
   - Click on a cell in the opponent's grid to fire a shot.
   - The game will indicate whether the shot was a hit or a miss.
   - The computer will then take its turn.

4. **Win the Game:**
   - The game ends when all of one player's ships are sunk.
   - The player who sinks all of the opponent's ships first is the winner.

## Future Enhancements

- **Improved AI:** Enhance the computer's strategy for placing ships and taking shots.
- **Multiplayer Mode:** Implement a two-player mode to allow for player vs. player gameplay.
- **Enhanced UI:** Improve the user interface with better graphics and animations.

## Acknowledgments

- [Battleship Game Rules](https://en.wikipedia.org/wiki/Battleship_(game))
- [JavaScript Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
