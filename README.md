# Pacman-JS-Game

A browser-based Pac-Man style game built with HTML5 Canvas and vanilla JavaScript.

## Gameplay

- Renders a maze using a grid-based map and image tiles.
- Controls a yellow Pac-Man player with smooth movement and mouth animation.
- Collects pellets to increase score.
- Picks up power-ups to make ghosts vulnerable.
- Includes ghost enemies with simple pathfinding and collision detection.
- Displays game over and victory conditions.

## Controls

- `W` = move up
- `A` = move left
- `S` = move down
- `D` = move right

## Project Structure

- `src/index.html` — game page and canvas container
- `src/styles.css` — minimal styles for canvas and score display
- `src/index.js` — game engine, map generation, rendering, movement, collision detection, and score tracking
- `src/img/` — image tiles used for maze boundaries

## Features Implemented

- Canvas rendering for player, ghosts, pellets, power-ups, and maze boundaries
- Tile-based maze generation from a grid map
- Player movement, rotation, and collision handling
- Ghost movement and frightened mode
- Score tracking with UI updates
- Win/loss conditions and power-up behavior

## How to Run

1. Open `src/index.html` directly in a browser, or
2. Serve the `src/` folder with a local web server for best results.

## Contributions

- `Icefowz` — project author and lead developer; implemented the game mechanics, maze rendering, collision system, and ghost behavior.
- Current README and documentation updates prepared for the repository.

## Contributors

- Icefowz
- Open-source contributors and collaborators

> Note: This README was updated to match the current project implementation in `src/index.js`, including game mechanics, controls, and feature descriptions.
