# 3D Space Shooter Web Game

A browser-based 3D space shooter built with Three.js. Fight enemies, dock at space stations, trade, and upgrade your ship!

## Features

- 3D space environment
- Player spaceship with movement and shooting
- Enemy ships with basic AI
- Dockable space stations for trading and upgrades
- Modular and extensible code structure

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the development server:
   ```bash
   npm run dev
   ```
3. Open [http://localhost:8080](http://localhost:8080) in your browser.

## Project Structure

```
public/           # Static assets (models, textures, etc.)
src/
  core/           # Engine setup, main loop
  entities/       # Player, enemies, stations
  systems/        # Game logic (AI, trading, upgrades)
  ui/             # User interface
  index.js        # Entry point
```

## Dependencies

- [Three.js](https://threejs.org/)

## License

MIT
