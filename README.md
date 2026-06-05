# PATTERN RETRIEVAL

A hand-drawn crossword puzzle game built as a single HTML file.

## About

**PATTERN RETRIEVAL** is a signal-recovery crossword game inspired by hand-drawn instrument art. The aesthetic mirrors a vintage CRT oscilloscope / signal analyser — complete with barrel-shaped bezel, ruler scales, TARGET LOCKED gauge, and gold spine column.

**Theme:** SEND IT — spell out the signal across the crossword grid.

## How to Play

1. Open `index.html` in any modern browser — no install, no server needed.
2. **Click** a white cell to select it.
3. **Type** a letter to fill it. Green = correct, red flash = wrong.
4. Click the **same cell again** to toggle between Across / Down direction.
5. Click a **clue** in the list to jump to that word.
6. Use **TAB** to advance to the next empty cell in the word.
7. Use **Arrow keys** (→ / ↓) to change direction.
8. Use **BACKSPACE** to erase your last guess.

## Scoring

| Action | Points |
|--------|--------|
| Correct letter | +10 |
| Complete a word | +25 |
| Wrong letter | −5 |
| Hint used | −5 |
| Reveal word | −50 |

## Features

- Hand-drawn art aesthetic — Caveat font, cream/black/gold palette
- Barrel-shaped CRT bezel frame
- Ruler scale (0, 01, 1, 02, 2, 03, 3) on the left
- TARGET LOCKED gauge with tick marks at the top
- Gold E-spine column pre-revealed as the signal backbone
- Hint letters S, I, T pre-shown in the left column
- Bottom readout: `— 1176 | RUN: 0001 | VT100  STO:·`
- On-screen keyboard with used/correct letter tracking
- Win screen: CONVERGENCE COMPLETE | PATTERN RESTORED
- NEW RUN resets puzzle and increments run counter

## Files

```
pattern-retrieval/
└── index.html   ← entire game, single file, no dependencies
```

## Credits

Hand-drawn art by [@oceanord28](https://x.com/oceanord28)  
Built as a WL submission for the PATTERN RETRIEVAL collection on ETH.# pattern-retrieval
hand drawn art to game.
