# Picture Puzzle

A responsive, single-page idiom guessing game. Read each visual clue, type the familiar saying, and build your streak.

## Play

Open `index.html` in a modern browser. No build step, server, or JavaScript package is required.

## Game features

- 36 shuffled idiom puzzles across several categories
- Flexible answer matching that ignores spaces, punctuation, and apostrophes
- Three progressive hints per puzzle, with a smaller score reward for each hint used
- Score, streak, solved count, progress bar, skip button, and recent wins
- Responsive layout and reduced-motion support

## Picture clues

This first playable version uses composed emoji scenes as its picture clues. Generated raster artwork is deferred; the clue display is isolated so a future image library can be added without changing the guessing and scoring logic.

