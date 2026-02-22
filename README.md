# Number Guessing Game

A compact, polished Python game that challenges players to guess a secret number. It combines a friendly CLI, helpful hints, and an attempt tracker so the game is approachable for beginners and still fun to play.

## Features

- Clear, interactive command-line interface
- Adjustable difficulty (easy/medium/hard) via code (or extendable)
- Hints for higher/lower and attempt counting
- Minimal dependencies — runs with standard Python 3

## Quick Start

1. Install Python 3.8+ (if needed).
2. From the project folder, run:

```bash
python main.py
```

The game launches in your terminal and prompts you to guess the secret number.

## Gameplay

- The program selects a secret number each round.
- Enter guesses; you'll receive "higher" or "lower" hints.
- The game shows how many attempts you used when you win.

## Extend or Customize

- Change the secret number range or add a difficulty selector in `main.py`.
- Add score persistence or a high-score screen for more polish.

## Contributing

Contributions are welcome — open an issue or submit a PR with improvements.

## Files

- [main.py](main.py): Game entrypoint and core logic.
- [README.md](README.md): Project overview and usage.
