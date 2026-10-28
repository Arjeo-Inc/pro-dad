# xytoe

Dad's napping. His toe is out. You have a hammer.

A tiny toe-smashing clicker game, live at **[xytoe.com](https://xytoe.com)**.

## How it plays

- Tap the stage (or press Space/Enter) to swing the hammer. Each hit earns points × your multiplier.
- Every hit raises the multiplier by 0.2, up to ×5. Above ×2 you're in rampage mode.
- Hits less than a second apart build a combo, worth up to +50% bonus.
- Go 5 seconds without a hit and you lose a point and your multiplier.
- Spend points in the polish shop on nail colors. Progress is saved in your browser.

## Development

The whole app is `index.html`: plain HTML, CSS and JavaScript. All the graphics are CSS, the sound is synthesized with Web Audio, and there are no dependencies and no build step. Open the file in a browser to run it.

## Deployment

GitHub Pages serves the repository root from the `main` branch. The `CNAME` file maps it to xytoe.com, so a push to `main` is a deploy.
