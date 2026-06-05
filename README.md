# Dreamy Starry Sky Tree

A dreamy canvas animation featuring delicate tree branches with stars and crescent moons hanging from threads, set against a deep blue night sky.

## Features

- Procedurally generated tree branches growing from the bottom-right
- Stars and moons falling from the sky and attaching to branches via elastic threads
- Damped elastic bounce animation (stars overshoot, then slowly settle)
- Continuous swaying of branches and ornaments
- Background twinkling stars and floating dust particles
- Occasional shooting stars
- Responsive full-screen canvas

## Animation Timeline

1. **0-3.5s**: Tree branches grow from bottom-right
2. **3.5-7.5s**: Stars and moons fall from above, bounce on elastic threads, and settle
3. **7.5s+**: Everything sways gently, occasional shooting stars streak across the sky

## Tech

- Pure HTML5 Canvas + JavaScript (no dependencies)
- Offscreen canvas caching for moon crescent rendering
- Procedural tree generation with recursive branching
- Physics-inspired elastic bounce with damped oscillation

## Live Demo

👉 [https://3458096571.github.io/dreamy-sky-tree/](https://3458096571.github.io/dreamy-sky-tree/)
