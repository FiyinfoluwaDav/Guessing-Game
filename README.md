# Word Raider

A simple and fun word guessing game built with Python in a Jupyter Notebook.

## Description

Word Raider is a classic word guessing game where you have to guess a secret 5-letter word. You have a limited number of attempts to guess the word correctly. With each guess, you'll get feedback on which letters are correct and in the right position, which letters are in the word but in the wrong position, and which letters are not in the word at all.

## Features

- **Simple Gameplay:** Easy to understand and play.
- **Limited Attempts:** You have 5 chances to guess the word.
- **Helpful Feedback:**
    - Correct letters in the correct position are revealed.
    - Misplaced letters (correct letters in the wrong position) are listed.
    - Incorrect letters are listed.
- **Word Bank:** The game uses a predefined list of words from `words.txt`.

## How to Play

1.  The game will choose a random 5-letter word.
2.  You have 5 turns to guess the word.
3.  Enter your 5-letter guess when prompted.
4.  The game will provide feedback on your guess:
    -   Letters that are in the correct position will be displayed.
    -   Letters that are in the word but in the wrong position will be listed as "Misplaced Letters".
    -   Letters that are not in the word will be listed as "Incorrect Guesses".
5.  If you guess the word correctly, you win!
6.  If you run out of turns, the game is over, and the secret word is revealed.

## Getting Started

To run the game on your local machine, you'll need to have Python and Jupyter Notebook installed.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/FiyinfoluwaDav/Guessing-Game.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Guessing-Game
    ```
3.  **Open the Jupyter Notebook:**
    ```bash
    jupyter notebook "Guessing Game.ipynb"
    ```
4.  Run the cells in the notebook to play the game.

## Dependencies

- Python 3
- Jupyter Notebook

## Future Improvements

- Add different difficulty levels (e.g., longer words, fewer attempts).
- Expand the word list in `words.txt`.
- Create a graphical user interface (GUI) for a more interactive experience.
- Add a scoring system.
