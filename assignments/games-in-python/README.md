# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a classic word-guessing game using Python strings, loops, conditionals, and user input. Practice selecting a random word, tracking guesses, and responding to the player's progress.

## 📝 Tasks

### 🛠️ Set Up the Game

#### Description
Prepare a word for the player to guess and initialize the game state.

#### Requirements
Completed program should:

- Store a predefined list of words and randomly select one word for each game.
- Track the letters guessed by the player and the number of incorrect guesses remaining.
- Display the hidden word as underscores, with spaces between each position (for example, `_ _ _ _`).

### 🛠️ Run a Round of Hangman

#### Description
Build the game loop so the player can guess letters until they reveal the word or run out of attempts.

#### Requirements
Completed program should:

- Prompt the player to enter a letter and show the current word progress after each guess.
- Reveal matching letters in the word and reduce the remaining attempts for an incorrect guess.
- End the game when the player guesses the word or has no attempts remaining.
- Display a win message when the word is guessed and a lose message when attempts run out.
