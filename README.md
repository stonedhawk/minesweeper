# Minesweeper

![Screenshot](screenshot.png)

A browser-based classic Minesweeper game with retro Windows styling. Single HTML file, zero dependencies.

## How to play

| Action | Control |
|--------|---------|
| Reveal a cell | Left click |
| Place / remove a flag | Right click |
| Reset game | Click the smiley button |
| Reset game (keyboard) | R |
| Switch to Easy | 1 |
| Switch to Medium | 2 |
| Switch to Hard | 3 |

## Features

- **3 difficulties** - Easy (9x9, 10 mines), Medium (16x16, 40 mines), Hard (16x30, 99 mines)
- **Recursive flood fill** - clicking an empty cell reveals all connected empty regions
- **First-click safety** - mines are placed after your first click, so you never hit one immediately
- **Flag system** - right-click to mark suspected mines; mine counter updates live
- **Timer** - starts on first click, stops when you win or lose
- **Smiley states** - normal, surprised (while clicking), dead (loss), cool (win)

## How to run

Just open `index.html` in any modern browser. No server, build step, or dependencies required.

## Tech stack

- React 18 (via CDN)
- Babel standalone (JSX transpilation)
- HTML5 / CSS3 / Vanilla JS
- Single `index.html` file

## Live demo

[https://stonedhawk.github.io/minesweeper](https://stonedhawk.github.io/minesweeper)

## License

MIT - see [LICENSE](LICENSE)
