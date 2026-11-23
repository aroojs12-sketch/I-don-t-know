# I Don't Know: Random Chaos

A small browser game where you survive as long as you can while the rules change every 10 seconds.

### ▶ [Play online](https://aroojs12-sketch.github.io/I-don-t-know/)

Opens in your browser. Nothing to download. Play with the keyboard, a mouse or a trackpad.

You are a blue square with a **?** on it. Dodge the red enemies, grab the yellow coins, and try to keep up when the game suddenly flips your controls, turns off the lights or makes you giant.

## Play without internet

1. Download this repository (green **Code** button → **Download ZIP**) and unzip it.
2. Double-click **`I-Dont-Know-Game.html`**. It opens in your web browser.
3. Press **Space** or click the game to start.

Nothing needs to be installed. You can also open `index.html`, but it needs `game.js` in the same folder.

## Controls

| Action | Keyboard | Mouse / trackpad |
| --- | --- | --- |
| Move | Arrow keys or W A S D | Move the pointer over the game. Your square sits right under it |
| Start / play again | Space or Enter | Click the game |

Pressing a movement key switches back to keyboard control. When **Controls Flipped!** is on, the square goes to the opposite side of the screen from your pointer. On **Ice Floor!** it slides after the pointer instead of jumping to it.

## Rules

- You start with **5 lives**. Touching a red enemy costs one life, and you blink for a moment while you can't be hit again.
- Yellow coins are worth **10 points**. They disappear after a few seconds.
- You also get **1 point per second** you survive.
- Enemies get faster the longer you last.
- Your best score is saved in your browser.

## Chaos events

Every 10 seconds one of these happens at random and lasts until the next one:

| Event | What it does |
| --- | --- |
| Controls Flipped! | Your movement keys are reversed |
| Gravity Down! / Gravity Up! | You get pulled toward the bottom or top |
| Enemies Are Friends! | Enemies turn green and give 5 points when you touch them |
| Enemies Speed Up! | Enemies move much faster |
| Enemy Party! | Enemies appear four times as often |
| Tiny You! / Giant You! | Your square shrinks or grows |
| Ice Floor! | You slide around |
| Lights Out! | You can only see a small circle around you |
| Upside Down World! | The screen flips upside down |
| Coin Rain! | Coins appear much faster |
| Slow Motion! / Turbo Mode! | The game slows down or speeds up |

## Change the game

Open `game.js` in any text editor. At the top you'll find:

- **`SETTINGS`**: speed, lives, how often chaos happens, points and more.
- **`COLORS`**: the colors of everything on screen.
- **`CHAOS_EVENTS`**: the list of chaos events. Copy a line to add your own.

`I-Dont-Know-Game.html` is a copy of `index.html` and `game.js` combined into one file, so changes to `game.js` don't show up in it automatically.
