# Chaos Sandbox

A falling-sand cellular-automaton playground. Paint elements, watch them react,
and build floating islands. Everything is one self-contained file — **just open
`chaos_sandbox.html` in a browser to play.** No install, no build step.

## How to play

Pick an element, then click and drag on the canvas to paint. Each pixel follows
tiny local rules, so all the drama (fire spreading, lava meeting water, acid
eating through walls) is emergent.

## Elements

Sand · Water · Stone · Wood · Fire · Oil · Lava · Ice · Plant · Acid · TNT ·
Glass · Bolt (lightning) · Chaos · **Levitite**

## Features

- **Tools** — Paint, Erase (with its own width slider), and Select.
- **Select tool** — drag a box, then **Copy · Cut/Move · Paste · Delete**, or
  toggle **Gravity Off / Gravity On** for the selected blocks.
  Keyboard: `C` copy, `X` cut, `V` paste, `Delete` clear, `Esc` cancel.
- **Levitite** (light-cyan, glowing) — the floating block. One Levitite lifts 9
  blocks:
  - balanced → the structure **floats**
  - too few Levitite → it **falls**
  - too many → gravity **inverts** and it rises (faster the more unbalanced)
  - a lone Levitite just floats. A "Gravity Off" block anchors a Levitite island.
- **Canvas sizes** — Small / Medium / Large / XL. Switching keeps what fits.
- **Auto-detonate** (Settings) — let unstable blocks (TNT) self-detonate, with
  adjustable chance % and interval in seconds.

## Field notes

- Fire is hungry. Oil is generous.
- Lava and water argue. Stone wins.
- Lightning turns sand into glass (fulgurite!).
- Acid eats almost everything. Almost.
- The chaos element does what it wants.
