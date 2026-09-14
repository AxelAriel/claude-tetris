# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

Vanilla-JS Tetris, no build step: `index.html` (DOM + board/preview canvases), `style.css`,
`game.js` (all game logic). `README.md` documents the mechanics and the tunable constants.

## Constraints

- **Zero dependencies.** No npm, bundler, transpiler, or framework — plain HTML/CSS/JS loaded
  directly by the browser. Don't introduce a `package.json`.
- Write new code, comments, docs, and user-facing strings in **English**. Existing Spanish text
  in `README.md`, `index.html`, and `game.js` stays as-is — don't translate it unless asked.
  When editing an existing Spanish README section, keep that section's language consistent.
- Update `README.md` when controls, scoring, tunable constants, or game behavior change.

## Verifying changes

There is no test suite and no lint step. After changing game logic, open the game in a browser
and confirm it runs and plays without console errors before reporting the change as done.

## Commits

Conventional Commits (`feat:`, `fix:`, `docs:`, `refactor:`). Work on a feature branch off
`main` rather than committing directly to `main`.
