# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a classic Hangman game in Python using strings, loops, conditionals, and user input. You will practice managing game state and creating a complete interactive command-line game.

## 📝 Tasks

### 🛠️ Build the Core Hangman Loop

#### Description
Create the main game flow that selects a hidden word, accepts one-letter guesses, and updates the displayed progress after each turn.

#### Requirements
Completed program should:

- Randomly select one word from a predefined list.
- Display the hidden word using underscores for unguessed letters (for example: `_ _ _ _`).
- Accept a single letter guess from the player on each turn.
- Reveal all matching positions when a correct letter is guessed.


### 🛠️ Add Win/Loss Rules and Feedback

#### Description
Implement attempt tracking and end-of-game logic so the player can win by guessing the full word or lose after too many incorrect guesses.

#### Requirements
Completed program should:

- Track and display the number of incorrect guesses remaining.
- Reduce remaining attempts only when the player enters an incorrect letter.
- End the game with a win message when all letters are revealed.
- End the game with a loss message when attempts reach zero and show the correct word.
