# Tower Tactix

A browser-based tower defense game. Defend the path from waves of demons and bosses using towers, heroes, and banks.

## How to play

1. Open **`index.html`** in a modern browser (Chrome, Firefox, Safari, Edge).
2. Choose a hero (or skip), then pick a game mode.
3. Place towers and banks on the map, then start waves. Upgrade towers along two paths (Path A or B) and use your hero’s ability when it’s ready.
4. Survive all waves to win; lose if your lives reach zero.

## Features

- **5 tower types**: Dart, Cannon, Ice, Sniper, Laser — each with two upgrade paths and 5 tiers.
- **Banks**: Earn cash over time; upgrade for more income per wave.
- **4 heroes**: Blaze, Frost, Zeus, Titan — each with a unique ability and two upgrade paths.
- **3 modes**:
  - **Normal** — 10 waves.
  - **Boss Easy** — 40 waves, 4 boss waves (every 10th).
  - **Boss Hard** — 80 waves, 8 boss waves, tougher scaling.
- **Save / Load** — 3 slots stored in the browser (localStorage).
- **Controls**: Start wave, auto-start next wave, speed (1–4×), pause, hero ability, sell, save panel. Works with mouse and touch.

## Tech

- Single HTML file: inline CSS and JavaScript, no build step.
- Canvas 2D for rendering; `requestAnimationFrame` game loop.
- Runs offline after the file is loaded.

## Repository

[https://github.com/gamebuilder26/Tower-Tactix](https://github.com/gamebuilder26/Tower-Tactix)
