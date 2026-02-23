The preview environment is now configured. Here's a summary of what was set up:

- **Warmup script**: Runs `npm ci` to install all dependencies (Phaser 3, Vite, TypeScript)
- **Run script**: Starts the Vite dev server bound to `0.0.0.0:3000` so it's accessible from the preview URL

The game should be available at the preview URL once the environment starts up. You'll be able to play the Zombie Survival game directly in the browser using WASD/Arrow keys to move and R to restart when dead.