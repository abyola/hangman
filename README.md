Here's a step-by-step guide on how the Hangman game is typically played:

## Objective
The goal of the game is to guess a hidden word by suggesting letters within a limited number of guesses.

Steps to Play Hangman
### Start the Game:

The game begins by selecting a random word from a predefined list (like the words module in your code).
### Display Initial State:

The word is represented by dashes (e.g., if the word is "APPLE," it will show as "-----").
Players are informed of the letters they have already guessed (initially empty).
### Player's Turn:

The player is prompted to guess a letter.
The input is converted to uppercase to maintain consistency.
### Check the Guess:

The game checks if the guessed letter:
- Is valid: It must be an alphabet letter and not already guessed.
- Is in the word: If it is, the corresponding dashes are replaced by the letter.
- If it’s not in the word, the player is notified that the letter is incorrect.
### Update Game State:

The game updates the display:
- Shows the current state of the word with correctly guessed letters filled in.
- Shows all letters guessed so far.
The game continues until one of the following conditions is met:
- Win Condition: The player successfully guesses all the letters in the word.
- Loss Condition: The player reaches a predetermined number of incorrect guesses.
### End the Game:

- If the player wins, they see a congratulatory message.
- If the player loses, they are shown the correct word and a message indicating they’ve lost.