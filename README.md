# Explorer

<p align="center">
  <a href="https://fractalated.github.io/Explorer/"><strong>▶&nbsp;&nbsp;PLAY EXPLORER IN YOUR BROWSER</strong></a>
  <br>
  <a href="https://fractalated.github.io/Explorer/">https://fractalated.github.io/Explorer/</a>
</p>

A first-person walk around a randomly generated island, with sea cliffs, terraced
highlands, caves and forest. Every island is different, and one takes about 30 minutes
to explore on foot.

## Controls

| Key | Action |
|---|---|
| ↑ / ↓ | Walk forward / back |
| ← / → | Turn |
| Shift | Run |
| Click and drag | Look up and down |
| N | Generate a new island |
| F | Show frame rate and walking speed |
| H | Hide the help panel |

**On a phone or tablet:** borderless, semi-transparent arrows appear at the bottom of the
screen. Use ◀ ▶ (bottom-left) to turn and ▲ ▼ (bottom-right) to walk, and double-tap and
hold ▲ to run. Drag a finger on the scene to look around, and tap ⟳ (top-right) for a new
island. The arrows only appear on touch devices and disappear if a keyboard is used.

Each island has a number, shown in the corner. It's also in the address bar
(`#seed=12345`), so you can bookmark or share a link to an island you like.

## What's on the island

- **Coastline**: sandy beaches in some places and sheer sea cliffs in others, with
  turquoise shallows, foam and open ocean out to the horizon
- **Highlands**: terraced hills with inland cliff bands
- **Caves**: several winding tunnels cut into the cliff faces, ending in a larger chamber
  with stalactites. Inside, your eyes adjust to the dark and a lantern comes on.
- **Forest**: pine and broadleaf woods, open meadows with wildflowers, and grass that
  sways in the wind
- **Sea**: walk into the water to swim. You can explore the coast or head out to
  the small islets offshore. Sheer sea cliffs can't be climbed, so swim back to a beach.
- **Sky**: a daytime sky with drifting clouds. The sun position changes from island to island.

## Running it locally

It's a single file, `index.html`. Open it in Chrome or Safari. It needs an internet
connection, because it loads [three.js](https://threejs.org) from a CDN.
