🎰 Python Slot Machine Game

A simple command-line slot machine simulation game built with Python. Players can deposit money, place bets on multiple lines, and spin the slot machine to test their luck!

🚀 Features

Deposit money into your balance.

Choose how many lines (1–3) to bet on.

Place bets with adjustable limits ($1 - $100).

Spin a 3x3 slot machine with symbols (A, B, C, D).

Winning lines are calculated with payouts based on symbol values.

Keeps track of your balance until you quit.

📂 Project Structure
slot_machine/
│── slot_machine.py   # Main game script
│── README.md         # Documentation

⚙️ How It Works

Deposit money to start.

Choose the number of lines you want to bet on (1–3).

Set your bet amount per line (min $1, max $100).

Spin the slot machine → Random symbols are generated.

Check winnings → If all symbols match across a line, you win!

Game continues until you quit (q) or balance runs out.

🎮 Gameplay Example
What would you like to deposit? $50
Enter the number of lines to bet on (1-3)? 2
What would you like to bet on each line? $10
You are betting $10 on 2 lines. Total bet is equal to: $20

D | A | B
C | A | A
B | D | C

You won $50.
You won on lines: 1
Current balance is $80
Press enter to play (q to quit).

🛠️ Requirements

Python 3.x

No external libraries required (uses only built-in random).

▶️ How to Run

Clone this repository:

git clone https://github.com/your-username/slot-machine-game.git
cd slot-machine-game


Run the game:

python slot_machine.py

📌 Future Improvements

Add diagonal winning lines.

Include colors or emojis for symbols.

Save user progress to a file.

Add betting multipliers and jackpots
