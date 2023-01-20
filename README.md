## Hangman Game

This is my coding challenge submission for day #7 of the 100 Days of Code: The Complete Python Pro Bootcamp, instructor-led training.

This Python code is a simple-but-fun game of Hangman. At the start of the game, the computer chooses one word randomly from the `word_list` imported from `hangman_words.py`, and the player has to guess letters in the word.

The player only has 6 lives - if they guess 6 letters which are not in the word, they will lose the game.

## How To Play
1. Run the code.
2. Guess a letter by entering it into the prompt. If the letter is in the word, it will be revealed in the spaces shown.
3. If the letter is not in the word, you lose one life (of 6 total lives).
4. When all the spaces have been filled and the_word_is complete, you win the game. If you run out of lives before completing the_word_, you lose the game.

At the start of the game, the logo from `hangman_art.py` is printed out. If you guess a letter that you've already guessed, you will be told. When you lose a life, the associated stage is printed out from `hangman_art.py`.

Good luck!

## Usage

```
 _                                             
| |                                            
| |__   __ _ _ __   __ _ _ __ ___   __ _ _ __  
| '_ \ / _` | '_ \ / _` | '_ ` _ \ / _` | '_ \ 
| | | | (_| | | | | (_| | | | | | | (_| | | | |
|_| |_|\__,_|_| |_|\__, |_| |_| |_|\__,_|_| |_|
                    __/ |                      
                   |___/
Guess a letter: l
You guessed l, that's not in the word. You lose a life.

...

Guess a letter: y
y _ m m y

  +---+
  |   |
  O   |
      |
      |
      |
=========


Guess a letter: u
y u m m y
You win.

  +---+
  |   |
  O   |
      |
      |
      |
=========
```
