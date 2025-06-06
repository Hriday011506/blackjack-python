🃏 Blackjack Game (Python Capstone Project)

Welcome to the Blackjack Game, a simple terminal-based version of the classic casino card game, built with Python! This project was created as a capstone to apply basic Python programming concepts such as functions, loops, conditionals, and list manipulation.

🎯 Game Objective

The goal of the game is to get a hand of cards as close to 21 as possible without going over. Try to beat the computer dealer!

📌 Features

Deck of cards with values from 2 to 11 (with face cards as 10 and Ace as 11 or 1)

Automatic score calculation

Special handling for Blackjack (21 with two cards)

Automatic computer strategy (dealer draws until score is at least 17)

Clean and readable structure using functions

Fun terminal interaction using emojis and user prompts

🧠 Concepts Used

Python Functions

Random module

List operations

Conditional statements (if, elif, else)

Loops (for, while)

Custom logic for Ace value handling (11 or 1)

ASCII art logo integration

🚀 How to Run

Make sure you have Python installed on your system. Then, clone the repository and run the file:

git clone https://github.com/Hriday011506/blackjack-python.git
cd blackjack-python
python blackjack.py

You may need to install or create an art.py file containing the logo variable if it’s not already included.

📂 File Structure

blackjack-python/

├── blackjack.py     # Main game script

├── art.py           # (Optional) ASCII logo art

└── README.md        # Project documentation

🎨 Sample Output

Your cards: [10, 7], current score: 17

Computer's first card: 9

Type 'y' to get another card, type 'n' to pass: n

Your final hand: [10, 7], final score: 17

Computer's final hand: [9, 5, 7], final score: 21

You lose 😤

📌 Notes

Blackjack is returned as a score of 0 to differentiate from regular 21.

The game clears the screen between rounds using print("\n" * 20) for a fresh interface feel.

