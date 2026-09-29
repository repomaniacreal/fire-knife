# 🔥 Fire Knife

A juicy single-file HTML5 knife-throwing game. Tap to hurl knives at a spinning log — but never hit a knife that's already stuck!

## How to Play

- **Tap the screen** (or press **Space**) to throw a knife at the spinning log
- Don't let your knife hit the knives already stuck in the log — your blade will shatter!
- **Slice 🍎 apples** for bonus apples
- Clear all your knives to trigger **STAGE CLEAR** — the log explodes into pieces
- Every 5th stage is a **BOSS STAGE**: faster spinning with sudden direction reversals

## Features

- Spinning log with dynamic rotation tricks: steady spin, pulsing speed, and sudden reversals
- Progressively harder stages: more knives, faster spin, pre-stuck knives
- Shattering knife physics, wood chips, confetti bursts, and screen shake
- Synthesized fire whooshes, thunks, and fanfares via the Web Audio API
- Persistent best score and apple collection (localStorage)

## Controls

| Input | Action |
|---|---|
| Tap / Click | Throw knife |
| Space | Throw knife |

## Run It

Just open `index.html` in any modern browser — no build step, no dependencies, no server required. Works with both mouse and touch.

## Tech

- Single HTML file, vanilla JavaScript + Canvas 2D
- Web Audio API for all sound effects
