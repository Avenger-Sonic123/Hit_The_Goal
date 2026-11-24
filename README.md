# Hit the Goal

A simple golf-inspired canvas game.

**Repository created:** 2021-08-27  
**Project status:** Learning project / historical snapshot  
**Earliest recorded commit (author date):** 2021-08-27

## Features and implementation

- Fabric.js ball and hole sprites.
- Arrow-key movement.
- Coordinate-based goal detection.
- Success message.

## Technologies

HTML, CSS, JavaScript, Bootstrap, jQuery, Fabric.js.

## How the code works

The `my_keydown()` handler calls `up()`, `down()`, `left()` and `right()` to move the ball on the Fabric.js canvas.

## Project structure

| File | Purpose |
| --- | --- |
| [`index.html`](index.html) | Main page and user interface |
| [`main.js`](main.js) | Project-specific JavaScript |
| [`style.css`](style.css) | Page styling |

Key functions in the source:
- `main.js`: `load_img()`, `new_image()`, `my_keydown()`, `up()`, `down()`, `left()`, `right()`.

## Run or explore locally

```bash
git clone https://github.com/Avenger-Sonic123/Hit_The_Goal.git
cd Hit_The_Goal
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser. The local server requires Python 3; browser-based dependencies may also require internet access.

Use arrow keys to move the ball toward the hole.

## Current status and limitations

Goal detection requires matching coordinates; no physics simulation.

---

Source reference: [`9765c5e2`](https://github.com/Avenger-Sonic123/Hit_The_Goal/tree/9765c5e24f497048c9445c92691a8e4e5bfac9d1) on `main`, verified against GitHub on 2026-11-24. Documentation is based on static source review; runtime behavior has not been tested.
