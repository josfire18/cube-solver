# Cube Solver

A phone-friendly Rubik's Cube (3×3) solver in one HTML file.

- Tap or drag across stickers to enter your cube one face at a time.
- **Auto-fill** places every sticker that only one color can fit, based on how a real cube is put together: each piece is unique, corners can't be twisted in place, edges can't be flipped, and two pieces can't be swapped alone.
- The status line shows how many different cubes still match what you've entered. Once only one does, the moves are worked out automatically.
- **Show steps** walks through the solution one move at a time on an animated 3D cube, with Previous, Replay and Next.

Solving uses Kociemba's two-phase algorithm from [cubejs](https://github.com/ldez/cubejs) (loaded from jsDelivr), run in a Web Worker.

## Use it

Open `index.html` in a browser. On iPhone, host it anywhere static (GitHub Pages works) and use Share → Add to Home Screen.
