# Scrabble Terminal Game

A simple Scrabble game for the terminal.

## How to Play

Run the game:

```bash
python -m scrabble
```

## Commands

- `BOARD` - Show the game board
- `RACK` - Show your tiles
- `PLAY row col direction word` - Place a word
  - Example: `PLAY 7 7 H HELLO`
- `EXCHANGE letters` - Exchange tiles
  - Example: `EXCHANGE ABC`
- `PASS` - Skip your turn
- `SAVE filename` - Save game
- `LOAD filename` - Load game
- `HELP` - Show help
- `QUIT` - Exit game

## Example Game

```
Player 1's turn > RACK
Player 1's tiles: A B C D E F G
Score: 0

Player 1's turn > PLAY 7 7 H HELLO
Placing word HELLO...

Player 1's turn > BOARD
=== GAME BOARD ===
[Board will show here]
```

## Team Project

This CLI is part of a team project. Other components:

- Board and game logic (P2)
- Rules validation (P3)
- Scoring system (P4)
- Project integration (P1)


