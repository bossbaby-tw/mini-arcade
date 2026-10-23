# Mini Arcade

Three quick browser games built with HTML, CSS, and JavaScript. No installation or build needed.

| Game | Play online | Local file |
| --- | --- | --- |
| Pocket Kart — Sunset Circuit | [Play racer](https://pocket-kart-sunset-1023.starryhorse7.chatgpt.site) | `pocket-kart/index.html` |
| Little Slide | [Play puzzle](https://little-slide-puzzle-1023.starryhorse7.chatgpt.site) | `little-slide/index.html` |
| Moonlit Sudoku — Witching Hour | [Play Sudoku](https://moonlit-sudoku-halloween.starryhorse7.chatgpt.site) | `moonlit-sudoku/index.html` |

## Play locally

Download or clone this repository, then open any game's `index.html` in a modern browser.

## Pocket Kart — Sunset Circuit

A three-lap arcade racer with four karts, golden boost pads, rechargeable boost, and touch controls.

| Control | Action |
| --- | --- |
| Left / Right or A / D | Steer |
| Space | Boost |
| Down | Brake |
| P | Pause / resume |

Acceleration is automatic. Touch controls appear on touch screens. Use Restart race to start over.

## Little Slide

Arrange the numbered tiles from 1 to 8, with the empty space at the bottom right. Click or tap a tile beside the empty space to slide it.

- New puzzle creates a solvable shuffle and resets the timer and move counter.
- Undo reverses your last move.
- The timer starts on your first move and stops when the puzzle is solved.

## Moonlit Sudoku — Witching Hour

Halloween anime-inspired Sudoku featuring Luna, an original little witch illustrated with inline SVG. Includes three difficulty levels, uniquely solvable generated puzzles, pencil notes, three hints per puzzle, undo, mistake checking, and a timer.

Fill every row, column, and 3×3 box with the numbers 1–9 exactly once.

| Control | Action |
| --- | --- |
| Click / tap a square | Select a cell |
| 1–9 or on-screen number buttons | Enter a number |
| Arrow keys | Move selection |
| N or Notes button | Toggle pencil notes |
| Backspace / Delete or Erase | Clear selected editable cell |
| Undo | Reverse the last edit |
| Hint | Reveal a correct number |
| New spell | Generate another puzzle |

Fixed numbers cannot be edited. The timer starts on the first edit. A new puzzle replaces the current puzzle after confirmation when play has started.

## Project structure

```text
pocket-kart/index.html     # Racing game
little-slide/index.html    # Sliding puzzle
moonlit-sudoku/index.html  # Halloween Sudoku
README.md                  # Play links and instructions
```

Each game is self-contained. Pocket Kart and Moonlit Sudoku optionally load fonts from Google Fonts and fall back to system fonts.
