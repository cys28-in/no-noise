# No-Noise: Smarter Comment Blurrer

A userscript that automatically blurs negative comments and highlights positive ones on **YouTube**, **Reddit**, and **Instagram**.

- **Negative comments** (with keywords like `"cringe"`, `"hate"`) are blurred and can be revealed on click.  
- **Positive comments** (with keywords like `"awesome"`, `"love"`) are highlighted.

## Features

- Customizable keyword lists via:
  - `window.NoNoise.setNeg()` – set negative keywords  
  - `window.NoNoise.setPos()` – set positive keywords
- Works on **YouTube**, **Reddit**, and **Instagram**
- Easy reset with `window.NoNoise.reset()`
- Install with **Tampermonkey** or a similar userscript manager.
