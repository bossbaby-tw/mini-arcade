# Mini Arcade

Five quick browser games built with HTML, CSS, and JavaScript. No installation or build needed.

| Game | Play online | Local file |
| --- | --- | --- |
| Pocket Kart — Sunset Circuit | [Play racer](https://pocket-kart-sunset-1023.starryhorse7.chatgpt.site) | `pocket-kart/index.html` |
| Little Slide | [Play puzzle](https://little-slide-puzzle-1023.starryhorse7.chatgpt.site) | `little-slide/index.html` |
| Moonlit Sudoku — Witching Hour | [Play Sudoku](https://moonlit-sudoku-halloween.starryhorse7.chatgpt.site) | `moonlit-sudoku/index.html` |
| Anime Afterhours — Character Club | [Play character quiz](https://anime-afterhours-character-club.starryhorse7.chatgpt.site) | `anime-afterhours/index.html` |
| Star Trail — Find Your Hero | [Play board game](https://star-trail-anime-adventure.starryhorse7.chatgpt.site) | `star-trail/index.html` |

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

## Anime Afterhours — Character Club

Guess 47 characters from 12 universes, including Naruto, Sanrio, Demon Slayer, Studio Ghibli, Ouran Host Club, Saiki K., Attack on Titan, and Gintama.

- Choose one or more universes and play up to ten distinct characters per round.
- Portrait mode shows the artwork; Mystery mode starts blurred.
- Use keys 1–4 or answer buttons to guess. H reveals a hint, and Enter advances after an answer.
- Correct answers earn points; hints reduce base points and consecutive correct answers earn streak bonuses.
- Browse the character library and artwork credits in the game. Best score is saved in your browser.

Unlike the single-file games, this game loads its character data from JSON. Serve the repository with a static server, then visit `/anime-afterhours/`. For example: `python3 -m http.server 8000` and open `http://localhost:8000/anime-afterhours/`.

## Star Trail — Find Your Hero

A simple anime-themed self-discovery board game for kids, designed for ages 7+. Roll a three-sided star die, travel toward Star Academy, and answer eight everyday-choice questions. The final card reflects four fictional hero styles: Explorer, Heartkeeper, Dreamweaver, and Star Scholar. Ties produce a mixed hero card, and any question can be skipped.

Optional feelings check-ins are not scored. This game is not an MBTI assessment, a validated personality test, a diagnosis, or mental-health screening. Results describe game choices, not fixed traits. Answers are kept only in the current session. A short grown-up guide is included in the game.

Open `star-trail/index.html` in a browser to play locally. No installation or build step is required.

## Project structure

```text
pocket-kart/index.html     # Racing game
little-slide/index.html    # Sliding puzzle
moonlit-sudoku/index.html  # Halloween Sudoku
anime-afterhours/           # Character quiz, data, and portrait assets
star-trail/index.html       # Kids’ anime board game
README.md                  # Play links and instructions
```

Each game includes its own gameplay assets. Pocket Kart, Moonlit Sudoku, and Anime Afterhours optionally load fonts from Google Fonts and fall back to system fonts. Anime Afterhours uses locally included portraits; its in-game credits link to AniList and official Sanrio character references.
