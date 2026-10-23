# Mini Arcade

Two quick browser games built with HTML, CSS, and JavaScript. No installation or build needed.

| Game | Play online | Local file |
| --- | --- | --- |
| Pocket Kart — Sunset Circuit | [Play racer](https://pocket-kart-sunset-1023.starryhorse7.chatgpt.site) | `pocket-kart/index.html` |
| Little Slide | [Play puzzle](https://little-slide-puzzle-1023.starryhorse7.chatgpt.site) | `little-slide/index.html` |

## Play locally

Download or clone this repository, then open either game's `index.html` in a modern browser.

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

## Project structure

```text
pocket-kart/index.html   # Complete racing game
little-slide/index.html  # Complete sliding puzzle
README.md                # Play links and instructions
```

Each game is self-contained. Pocket Kart optionally loads its font from Google Fonts and falls back to the system font.
