# Minesweeper

A browser-based classic Minesweeper game with retro Windows styling. Single HTML file, zero build dependencies.

## What we're building

- Classic Minesweeper with three difficulty levels:
  - Easy: 9x9 grid, 10 mines
  - Medium: 16x16 grid, 40 mines
  - Hard: 16x30 grid, 99 mines
- Header bar: mine counter (left), smiley reset button (center), timer (right)
- Digital font style for counter and timer (monospace, red on dark background)
- Difficulty selector above the board
- Classic raised/sunken 3D cell styling
- First-click safety: mines never spawn on the clicked cell or its 8 neighbors
- Recursive flood-fill reveal for empty cells
- Right-click flagging with mine counter tracking
- Win/loss detection with smiley face states
- Timer starts on first click, stops on win/loss

## Tech

- React 18 via CDN (no build step)
- Babel standalone for JSX transpilation
- All code in a single index.html file
- No external CSS frameworks

## Difficulties

| Difficulty | Rows | Cols | Mines |
|-----------|------|------|-------|
| Easy      | 9    | 9    | 10    |
| Medium    | 16   | 16   | 40    |
| Hard      | 16   | 30   | 99    |

## Constraints

- No em dashes in comments or text
- Single HTML file, zero npm dependencies
- Must work in Chrome, Firefox, Safari
- Dark themed page, centered game container
- Classic Minesweeper aesthetic (not Material/flat design)
