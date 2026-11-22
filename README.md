# Jono JSON Editor

A community level editor for **Jono** that runs in your browser. Draw a level, add hazards and switches, then download
the JSON and load it in the game. Everything runs on your own computer: no account, nothing is uploaded.

This is a community tool, not the official in-game editor.

## Use it
- **Online:** open the GitHub Pages link for this repository (see the About box on the right).
- **Offline:** download `index.html` and open it in any modern browser.

Press **?** in the editor for shortcuts.

## What's new in v0.5
- **New items:** ladders, jump orbs, wind and lasers.
- **TANDEM items:** checkpoints, hold plates and plates for two. Also mega bouncers, trap floors and trap blocks.
- **TANDEM mode:** choose JONO, MEAT GRINDER or TANDEM under *Level settings*.
- **Mode limits:** a table showing how many of each item the level uses, next to what JONO and TANDEM allow. Items
  that go over a limit are shown in red.
  - The object picker shows each item's count against its limit, and dims items the mode doesn't allow.
  - The level check lists every rule the level breaks for its mode: size, items allowed only in some modes, and
    per-item caps.
- **Lasers aim themselves** like in the game: the beam stops at the first wall. Press **▶ All** to watch lasers
  switch on and off and wind blow.

## Mode limits (game defaults)
|                    | JONO      | MEAT GRINDER | TANDEM    |
|--------------------|-----------|--------------|-----------|
| Map size           | 512 × 512 | 512 × 512    | 128 × 128 |
| Your clear (submit)| 30 s      | 5:00         | –         |
| Per-item caps      | yes       | none         | yes       |

These limits apply in every mode:
- at most 40,000 tiles;
- at most 400 things in a submitted level;
- trigger numbers 0–119;
- one spike wall;
- moving things must line up again within 120 s.

The per-item caps are in the editor's *Mode limits* panel. They are the game's built-in defaults; the live server can
change them.
