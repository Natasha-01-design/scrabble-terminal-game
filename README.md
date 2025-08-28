# Scrabble Terminal Game

A Python-based Scrabble game that runs in the terminal with PostgreSQL database integration for game state persistence.

## Team Members

This project was developed as a collaborative effort with the following team members and their responsibilities:

- **Jayden Petee** - Game board, tile bag, rack system and turn loop implementation
- **Lincoln Ngugi** - Letter scoring system and score calculations
- **Paul Kimani** - Game rules validation, word placement and connectivity checks
- **Jerry Omweno** - CLI/UX interface, input/output handling and project packaging
- **Natasha** - Database design and implementation

## Setup Instructions

1. Install dependencies:
```bash
pipenv install
```

2. Activate the virtual environment:
```bash
pipenv shell
```

3. Set up your PostgreSQL database and update the `.env` file with your database credentials.

4. Run the game:
```bash
python main.py
```

## Game Features

- **Player Registration**: Create account with username, country, and password
- **Game Persistence**: Save and load game states using PostgreSQL database
- **Human vs Computer**: Play against a computer opponent
- **Word Validation**: Built-in dictionary for word verification
- **Scoring System**: Standard Scrabble scoring with multiplier tiles
- **Interactive Board**: 15x15 game board with special multiplier squares
- **Rack Management**: 7-tile rack with automatic refilling

## How to Play

1. Enter your username and password (or create new account)
2. Choose to play against computer or solo
3. View your tile rack and the game board
4. Enter words with row, column, and direction (H/V)
5. Game automatically validates placement and calculates scores
6. Continue until maximum turns reached or no valid moves available

## Game Commands

- Enter a word to play it on the board
- Type `quit` or `exit` to save and exit the game
- Type `reset` to get new tiles in your rack
- Follow prompts for word placement (row, column, direction)

## Technical Details

- **Language**: Python 3.8+
- **Database**: PostgreSQL with SQLAlchemy ORM
- **Dependencies**: psycopg, sqlalchemy, alembic, python-dotenv
- **Architecture**: Modular design with separate components for game logic, board, scoring, and database operations


