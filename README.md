# Applied Resilience — Games

Interactive NYT-style games for the **Applied Resilience** course at SCET, UC Berkeley (Vicky Howell).

Built for the year-end Carnival.

## Games

### Crossword
6 themed crossword puzzles covering all course lectures. Features a tiered hint system:
1. **Reveal a letter** — one random unfilled letter appears
2. **Source hint** — shows which lecture the word comes from
3. **Unscramble** — the answer's letters, scrambled
4. **Keep revealing** — continues giving letters, one at a time

Includes pencil mode, check/reveal, timer, and progress saving.

### Connections
4 puzzles where you group 16 course terms into 4 categories of 4. Inspired by NYT Connections — includes "one away" feedback, lives system, and shuffle.

### Word Guess
Wordle-style game with 5-letter course terms. Guess the word in 6 tries with color-coded feedback. After each game, the course clue and lecture source are revealed.

## Setup

Open `index.html` in a browser. No build step, no dependencies — everything is in one file.

## Data

All clues and answers are sourced from `crossword_bank.md`, which covers Lectures 1-10, 13, and the Carlson Mapping Workshop (160 total clues).
