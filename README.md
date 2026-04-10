# match3temp

> A Match-3 puzzle game template built with TypeScript.

## Overview

`match3temp` is a TypeScript-based template for building Match-3 style puzzle games (think Candy Crush or Bejeweled). This project provides the core game logic and structure that can be extended into a full game.

## Features

- Match-3 game board logic
- Tile swapping and match detection
- Score tracking
- Written in TypeScript for type safety and maintainability

## Tech Stack

| Technology | Purpose |
|---|---|
| TypeScript | Game logic & type-safe development |
| Node.js | Runtime environment |

## Prerequisites

- Node.js 16+
- npm or yarn

## Installation

1. **Clone the repository**

```bash
git clone https://github.com/bhupathirajusrija-rgb/match3temp.git
cd match3temp
```

2. **Install dependencies**

```bash
npm install
```

3. **Compile TypeScript**

```bash
npx tsc
```

4. **Run the project**

```bash
npm start
```

## Development

For live reloading during development:

```bash
npm run dev
```

## Project Structure

```
match3temp/
├── src/
│   ├── board.ts        # Game board logic
│   ├── tile.ts         # Tile definitions
│   ├── matcher.ts      # Match detection algorithm
│   ├── scorer.ts       # Score tracking
│   └── index.ts        # Entry point
├── tsconfig.json       # TypeScript config
├── package.json        # Dependencies
└── README.md           # Documentation
```

## How It Works

1. **Board Initialization** — A grid is filled with randomly assigned tiles
2. **Player Move** — Two adjacent tiles are swapped
3. **Match Detection** — The board checks for 3+ matching tiles in a row/column
4. **Clearing & Gravity** — Matched tiles are removed and tiles fall to fill gaps
5. **Scoring** — Points are awarded based on match size and combos

## Roadmap

- [ ] Add animations
- [ ] Add special tiles (bombs, row-clearers)
- [ ] Build a UI with HTML Canvas or a framework
- [ ] Add difficulty levels
- [ ] Leaderboard support

## Author

**Srija Bhupathiraju** — [@bhupathirajusrija-rgb](https://github.com/bhupathirajusrija-rgb)
