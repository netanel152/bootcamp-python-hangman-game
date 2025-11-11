# Hangman Game (Python)

A classic word-guessing Hangman game built in Python. This project was created as part of a Python bootcamp.

## Features

* **Classic Gameplay**: Guess letters to find the hidden word.
* **Limited Lives**: You'll have to guess the word before you run out of attempts!
* **Random Word Selection**: The game randomly picks a word from a predefined list, so every game is different.
* **Simple & Fun**: A text-based game that runs directly in your terminal.

## How to Play

To run this game on your local machine, follow these simple steps.

### Prerequisites

You must have **Python 3** installed.

### Installation & Running

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/netanel152/bootcamp-python-hangman-game.git](https://github.com/netanel152/bootcamp-python-hangman-game.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd bootcamp-python-hangman-game
    ```
3.  **Run the game:**
    ```sh
    python hangman.py
    ```
    *(Note: If your main file is named something else, like `main.py`, use that command instead.)*

4.  **Enjoy!** Follow the prompts in the terminal to guess letters and solve the puzzle.

## Project Structure

The game is built with a single Python script (`hangman.py`) and uses the built-in `random` module to select words.

**Key Concepts Used:**
* `while` loops (to keep the game running)
* `for` loops (to iterate over the word)
* String manipulation
* Lists (to manage the displayed blanks)
* User input (`input()`)
* Conditional logic (`if`/`else`)

---
