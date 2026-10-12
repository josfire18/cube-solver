# Cube Solver

A phone-friendly Rubik's Cube (3×3) solver in one HTML file.

- Tap stickers right on the 3D cube to paint them. One finger turns the cube, two fingers twist it.
- **Camera scan:** photograph the white/green/red corner, then the yellow/orange/blue corner, lining the cube up with the outline. Colors are decided together so the result is always a real cube; one photo alone still leaves thousands of possibilities for the hidden faces.
- **Saved cubes:** name and save the current cube, load or delete saved ones.
- **Auto-fill** places every sticker that only one color can fit, based on how a real cube is put together: each piece is unique, corners can't be twisted in place, edges can't be flipped, and two pieces can't be swapped alone.
- The status line shows how many different cubes still match what you've entered. Once only one does, the moves are worked out automatically.
- **Solve** walks through the solution one move at a time: the cube turns to face the layer, an arrow shows the direction, and the layer turns. Each step replays on a loop until you tap Next or Previous.

Solving uses Kociemba's two-phase algorithm from [cubejs](https://github.com/ldez/cubejs) (loaded from jsDelivr), run in a Web Worker.

## Use it

Open `index.html` in a browser. On iPhone, host it anywhere static (GitHub Pages works) and use Share → Add to Home Screen.
