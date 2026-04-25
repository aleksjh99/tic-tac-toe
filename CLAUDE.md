# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository

Single-file browser game project. The entire application is `tictactoe.html` — no build step, no dependencies, no package manager.

## Development

Open `tictactoe.html` directly in a browser to run the game:

```
start tictactoe.html
```

## Git & GitHub

Remote: `https://github.com/aleksjh99/tic-tac-toe`

**After every change, always commit and push to GitHub.** No work should be left uncommitted.

- Stage only the relevant file(s) — never `git add -A` blindly
- Write short, clear commit messages in plain language, e.g. `Add restart button`, `Fix win detection bug`
- A hook automatically runs `git push` after every `git commit`, so no manual push is needed
