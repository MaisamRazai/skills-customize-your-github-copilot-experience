
# 📘 Assignment: Hangman Game

## 🎯 Objective

Build an interactive Hangman game in Python using loops, string handling, and user input to reinforce game logic and control flow.

## 📝 Tasks

### 🛠️ Word Selection and Display

#### Description

Create a function to select a random word from a predefined list and display the current guessed word state using underscores for unknown letters.

#### Requirements
Completed program should:

- Choose a random word from a list of at least five words.
- Show the word progress using underscores for unguessed letters (e.g. `_ a _ g m a n`).
- Update the displayed progress after each correct letter guess.

### 🛠️ Guess Handling and Attempts

#### Description

Accept letter guesses from the player, check them against the secret word, and track remaining attempts for incorrect guesses.

#### Requirements
Completed program should:

- Prompt the player to enter a single letter guess.
- Reduce the remaining attempts when the guess is incorrect.
- Prevent repeated penalties for letters already guessed.
- Display the number of attempts left after each guess.

### 🛠️ Win/Lose Game Flow

#### Description

Manage the game loop so it ends with a win when the word is fully guessed or a loss when attempts are exhausted.

#### Requirements
Completed program should:

- End the game with a success message when the player guesses the word.
- End the game with a failure message when the player runs out of attempts.
- Reveal the full word when the game ends.
- Display the number of correct and incorrect guesses made by the player.
