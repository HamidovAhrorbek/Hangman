🎯 Hangman - Python Terminal Game

This is a simple Hangman game built with Python. It's a terminal-based word-guessing game where the player tries to guess a secret word one letter at a time. The game ends when the player correctly guesses all letters or runs out of lives.


📌 Features

* Random word selection from a predefined list.

* ASCII art for visual feedback.

* Tracks lives and previously guessed letters.

* Win or lose messages displayed at the end of the game.


🚀 Getting Started

Prerequisites
Python 3.x installed on your machine


-- Files

Make sure you have the following files:

main.py (your main game file)

hangman_words.py (contains a list named word_list)

hangman_art.py (contains ASCII art for logo and stages)


-- Example hangman_words.py

word_list = ['python', 'hangman', 'challenge', 'programming']


-- Example hangman_art.py

stages = [
    # Final stage: head, torso, both arms, and both legs
    "  _______\n |       |\n O       |\n/|\\      |\n/ \\      |\n         |\n=========",
    # Add more stages...
]

logo = '''
 _                                             
| |                                            
| |__   __ _ _ __   __ _ _ __ ___   __ _ _ __  
| '_ \\ / _` | '_ \\ / _` | '_ ` _ \\ / _` | '_ \\ 
| | | | (_| | | | | (_| | | | | | | (_| | | | |
|_| |_|\\__,_|_| |_|\\__, |_| |_| |_|\\__,_|_| |_|
                    __/ |                      
                   |___/                       
'''


🕹️ How to Play
1. Run the script:

python main.py

2. A word is randomly chosen.

3. Guess one letter at a time.

4. You have 6 lives. Each incorrect guess loses a life.

5. The game ends when you either guess the word or run out of lives.


🛠️ Code Overview

The main logic resides in main.py, with a loop that:

* Prompts for input.

* Checks the guess against the chosen word.

* Updates the display and life count.

* Ends when either the word is guessed or no lives remain.


📸 Sample Output

Guess a letter: a
Word to guess: _ a _ _ _ _
****************************5/6 LIVES LEFT****************************
You guessed 'x', that's not in the word. You lose a life.










