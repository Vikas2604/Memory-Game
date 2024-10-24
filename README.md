# Memory Game

A simple memory matching game built using **JavaScript**, **HTML**, and **CSS**. The objective is to match pairs of cards by remembering their positions.

## How to Play

- Click on a card to flip it over.
- Click on another card to flip it as well.
- If the two cards match, they stay flipped.
- If they don't match, the cards will flip back after a short delay.
- The goal is to match all the card pairs and win the game.

## Features

- A 4x4 grid of cards (16 cards in total).
- Randomized card positions for each new game.
- Responsive feedback: matched pairs stay flipped while non-matching pairs reset.
- "Restart Game" button to reset the board and play again.
- Game won message when all pairs are matched.

## Demo

To play the game locally, follow the installation steps below.

## Installation

To run the Memory Game locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/Vikas2604/memory-game.git
2. Navigate to the project folder:
   ```bash
   cd memory-game
3. Open the index.html file in your web browser to start playing.

## Project Structure
   ```bash
memory-game/
│
├── index.html      # The main HTML file
├── style.css       # CSS file for styling
└── script.js       # JavaScript for game logic
```
## Technologies Used
1. HTML: To structure the game board.
2. CSS: For styling the cards and layout.
3. JavaScript: Implements the game logic, shuffling the cards, handling user interactions, and checking for matches.
