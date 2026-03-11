# MyProjects
projects
# 🎮 Python Number Guessing Game

A command-line Python game where the player tries to guess a randomly generated number between 1 and 100.  
The game provides feedback if the guess is too high or too low, includes difficulty levels, limited attempts, and a replay option.

---

## 📝 Features
- 🎲 Random number generation
- 🔢 Difficulty levels: Easy / Medium / Hard
- ⏱️ Limited attempts based on difficulty
- 📈 Feedback: "Too High" or "Too Low"
- ⚠ Input validation (prevents crashes)
- 🔄 Replay option to play multiple rounds

---

## 🛠️ Technologies Used
- Python 3
- `random` module
- `IPython.display` (for Colab-friendly screen clearing)

---

## 🚀 How to Run
1. Clone the repository or download the files.
2. Run the Python script:
```bash
python guessing_game.py

🎮 Welcome to the Number Guessing Game!
 Example OUTPUT
Select Difficulty Level
1. Easy (10 Attempts)
2. Medium (7 Attempts)
3. Hard (5 Attempts)
Enter choice (1/2/3): 2

I have selected a number between 1 and 100. You have 7 attempts.

Attempt 1: Enter your guess: 50
Too Low!

Attempt 2: Enter your guess: 80
Too High!

Attempt 3: Enter your guess: 70
Too Low!

Attempt 4: Enter your guess: 73
🎉 Congratulations! You guessed the number in 4 attempts!

Project Structure
number-guessing-game/
│
├── guessing_game.py      # Main game code
├── README.md             # Project documentation
└── screenshot.png        # Example output
