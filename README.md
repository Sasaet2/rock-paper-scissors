# Rock Paper Scissors (حجر ورقة مقص)

The classic game in the browser, with an Arabic interface and a dark
neon look. Play against the computer, track the score, and reset
whenever you like. One file, no build step, no dependencies beyond a
Google Font.

## Play

Open `index.html` in any browser - that's it.

## Features

- Arabic RTL interface with the Cairo font
- Live scoreboard (you vs. the computer)
- Win / lose / draw feedback with colors
- Reset button
- Responsive layout that works on phones
- Single `index.html`: HTML + CSS + JavaScript together

## How it works

Each button carries a `data-move` attribute. A click calls `play()`,
which picks the computer's move with `Math.random()`, compares it
against a small `beats` table, and updates the score and message.

## Testing status

Tested in Chrome: hundreds of simulated rounds confirmed the result
messages and the scoreboard always stay in sync.
