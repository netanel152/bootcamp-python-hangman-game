Hangman Game in Python 🐍

A classic word-guessing game built from scratch in Python. Guess the hidden word, one letter at a time, before you run out of lives!

This project is a step-by-step creation from a Python bootcamp, designed to practice core programming fundamentals.

  +---+
  |   |
  O   |
 /|\  |
 / \  |
      |
=========


🎮 Features

Classic Gameplay: A simple and addictive text-based word game.

Random Word Selection: The game randomly picks a word from a predefined list, making every session unique.

❤️ Lives System: You only have a limited number of guesses! Make them count.

ASCII Art: Visual feedback as the hangman is drawn with each incorrect guess.

Runs Anywhere: As a simple terminal application, it runs in any standard console.

🚀 How to Run

To get this game running on your local machine, just follow these simple steps.

Prerequisites

You must have Python 3 installed on your system.

Installation & Running

Clone the repository:

git clone [https://github.com/netanel152/bootcamp-python-hangman-game.git](https://github.com/netanel152/bootcamp-python-hangman-game.git)


Navigate to the project directory:

cd bootcamp-python-hangman-game


Run the game script:

python hangman.py


(Note: If your main file has a different name, like main.py, use that command instead.)

Start playing!

📜 Rules of the Game

The game will choose a secret word at random.

You will see a row of blanks (_) representing the letters in the word.

Guess a single letter and press Enter.

If the letter is in the word, it will be revealed in all its correct positions.

If the letter is not in the word, you will lose one life, and a new part of the hangman will be drawn.

You win by guessing all the letters in the word before you run out of lives.

You lose if the hangman is fully drawn!

🛠️ Key Concepts

This project is a practical exercise in Python fundamentals. The core of the game is built using:

while loops to control the main game flow and keep it running until the player wins or loses.

for loops to iterate over the word's letters.

String & List Manipulation to build and update the display of blanks and correct letters.

Conditional Logic (if/else) to check if a guess is correct, if the player has won, or if they are out of lives.

User Input (input()) to get the player's guess.

Modules (like random) to import word lists and other game assets.
