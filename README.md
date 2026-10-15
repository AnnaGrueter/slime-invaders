# Slime Invaders

A recreation of the 1992 Mac OS game **Slime Invaders** — a simple arcade shooter where players defend against descending slime enemies, dodge projectiles, and chase high scores.

I rebuilt it as a small experiment in **vibe coding and AI-assisted prototyping**, using a nostalgic game as a constrained way to explore how quickly modern tools can produce something interactive, stateful, and polished.

## Why I built it

The original appeal of Slime Invaders is its simplicity: quick gameplay, clear feedback, and the kind of lightweight fun early Mac games did well.

I wanted to see how effectively current AI-assisted tools could recreate that experience in the browser while still handling the details that make a game feel good — timing, collisions, difficulty, sound, menus, and score persistence.

The project was prototyped in **Bolt.new** and then refined into a client-side Next.js implementation.

## What it does

- Arcade-style shooting gameplay
- Descending enemy behavior
- Projectile and collision handling
- HTML Canvas rendering
- Persistent high scores
- Configurable difficulty
- Sound controls
- Interactive menu bar
- Responsive canvas scaling

## Tech

- Next.js / React
- Tailwind CSS
- HTML Canvas
- React Hooks
- Custom game and UI state
- `lucide-react`
- `clsx`
- `tailwind-merge`

## Architecture

The project separates gameplay state from UI state using custom React hooks.

Key areas include:
- game-loop timing
- enemy behavior
- collisions
- score state
- asset loading
- sound controls
- responsive canvas behavior

## What I was exploring

This project was less about rebuilding an old game perfectly and more about testing how AI-assisted development tools handle a small but interaction-heavy product.

A game is a useful test because working code is not enough. Timing, responsiveness, feedback, difficulty, and visual feel all need iteration.

The interesting part was seeing where AI accelerated implementation — and where human judgment was still needed to make the experience feel right.

## Demo

[Play Slime Invaders](https://slime-invader-gamepl-eey3.bolt.host/play)

_Add a screenshot or short GIF here._

## Inspiration

Inspired by the original **Slime Invaders** for Mac OS, released in 1992.
