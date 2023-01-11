# Hangman Game
This is a simple hangman game implemented in Python. The game randomly selects a word from a list of words and the user is prompted to guess the letters of the word. If the user guesses the correct letter, it is added to the word and the user can continue guessing. If the user guesses an incorrect letter, they lose a life. The user has 7 lives to guess the word correctly.

## How to run the game
1. Clone the repository to your local machine using the command git clone https://github.com/@nikhilsharma26500/hangman.git
2. Navigate to the repository's root directory using the command cd hangman
3. Run the command python hangman.py to start the game

## File Structure
- hangman.py - contains the main game logic and implementation
- words.py - contains the list of words that the game randomly selects from
- hangman_visual.py - contains the ASCII art for the different stages of the hangman game

## Dependencies
- Python 3.x
- random module
- string module

## Game Logic
The game starts by selecting a random word from the words list. The user is then prompted to guess a letter and the letter is checked against the selected word. If the letter is in the word, it is added to the word and the user can continue guessing. If the letter is not in the word, the user loses a life. The user has 7 lives to guess the word correctly. The game continues until either the user guesses the word correctly or runs out of lives.

## Game Interface
The game interface is simple and shows the user their remaining lives, the letters they have guessed, the current state of the word (with unguessed letters replaced by dashes) and a visual representation of the hangman game.

## Limitations
- The game only selects words from the predefined list of words, so the list of words has to be updated manually.
- The game does not check for the validity of the letters entered by the user.
- The game does not have an option to play again after a game has ended.
