# Nebula Brush

An interactive flow-field particle painter in a single HTML file. Thousands of
glowing particles ride a Perlin noise flow field; drag anywhere to attract them
like a brush herding a nebula across the canvas.

## Run

Open `index.html` in any browser. No build step, no dependencies.

## Controls

| Input | Action |
| --- | --- |
| Drag | Attract particles (switch to *Repel* in the panel to scatter) |
| `R` | Randomize palette, physics, and flow-field seed |
| `S` | Save the current frame as PNG |
| `C` | Clear the canvas |
| `Space` | Pause / resume |

Tweak particle count, flow scale, speed, trail persistence, and stroke width in
the panel. When left idle, a wandering attractor keeps painting on its own.

## License

MIT
