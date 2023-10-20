# Pig-Game-JS-

## Overview

The Pig Game is a simple web-based dice game where two players take turns rolling a dice to accumulate points. The objective is to reach a predefined score before your opponent. This project demonstrates a basic implementation of the Pig Game using HTML, CSS, and JavaScript.

## Features

The Pig Game offers the following features:

1. **Two Players**: The game supports two players who take turns rolling the dice.

2. **Roll Dice**: Players can click the "Roll Dice" button to roll a six-sided dice and accumulate points. The dice result is displayed on the screen.

3. **Hold Points**: Players can click the "Hold" button to add their current points to their total score. The turn then passes to the other player.

4. **Winning Condition**: The game continues until one player reaches or exceeds a predefined winning score (default: 100 points). The winning player is declared, and the game ends.

5. **Start New Game**: The "Start Game" button allows players to reset the game and start a new one.

## Code Structure

### HTML

- The HTML file defines the game's structure, including player sections, total scores, current scores, and buttons for rolling the dice, holding points, and starting a new game.

- CSS is used to style the elements, creating a visually appealing interface. Player sections are color-coded, and the dice image is displayed in the center.

### JavaScript

- The JavaScript code adds interactivity to the game. It manages player scores, tracks the active player, and handles dice rolls.

- When the "Roll Dice" button is clicked, a random number between 1 and 6 is generated to simulate a dice roll. The result is displayed on the screen.

- Players can accumulate points by clicking "Roll Dice," but if they roll a 1, their current score is reset to 0, and the turn passes to the other player.

- The "Hold" button allows players to add their current score to their total score. The game checks if the player has reached the winning score, and if so, declares the player as the winner.

- The "Start Game" button resets the game, allowing a new game to begin.

## Usage

To play the Pig Game:

1. Open the HTML file in a web browser.

2. Click "Start Game" to begin a new game.

3. Click "Roll Dice" to roll the dice, accumulating points.

4. Click "Hold" to add your current points to your total score.

5. The game continues until one player reaches or exceeds the winning score.

6. Click "Start Game" to reset and start a new game.

## Conclusion

The Pig Game is a fun and interactive two-player dice game. It serves as a basic example of web-based game development using HTML, CSS, and JavaScript. Players can enjoy taking turns, accumulating points, and competing to reach the winning score. The game can be customized with different winning score thresholds or additional features for a more complex game.

---
