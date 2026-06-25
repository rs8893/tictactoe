# Tic Tac Toe

A mobile-friendly Tic Tac Toe game playable against an AI opponent in the browser.

**Play it:** https://rs8893.github.io/tictactoe/

## How it works

- You play as **X** and go first
- The AI plays as **O** — it will win or block when it can, otherwise it picks randomly, so you can beat it
- Scores persist across sessions via localStorage
- Tap **New Game** to reset the board, **Reset Scores** to clear the scoreboard

## Tech

Single `index.html` file — no dependencies, no build step. Deployed automatically to GitHub Pages via GitHub Actions on every push to `master`.
