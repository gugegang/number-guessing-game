# Number Guessing Game

This was my fourth project, and I had fun making it! I built this simple Python game to practice what I was learning and see how I could turn it into a working program.

## What it does

The game asks you to pick a number from 1 to 10. The correct answer is always **6**. It tells you whether your guess is right or wrong. If you enter a number outside that range, it asks you to pick a number from 1 to 10.

After a guess from 1 to 10, it prints `Thanks for using my tool!`.

## How it works

- `print()` displays instructions and messages.
- `input()` reads the player's guess, and `int()` converts it to an integer.
- `if`, `elif`, and `else` check the guess and choose the response.
- The final check, `if num > 0 and num <=  10:`, makes sure the thank-you message appears for every number from 1 through 10, including 10.

The game gives you one guess each time you run it. It expects a whole number; entering letters or a decimal causes a `ValueError`.

## How to run

Install Python 3, open a terminal in the folder containing the game, and run:

```bash
python number_guessing_game.py
```

Then enter a whole number from 1 to 10.
