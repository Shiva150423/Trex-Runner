# T-Rex Runner — Full Package (Low-Poly GLB + Jungle Lighting)

This package contains:
- `index.html` — the Three.js game (uses embedded low-poly `models/trex.glb`)
- `models/trex.glb` — low-poly T-Rex model included
- `assets/` — includes `trex.png` (your image) and generated audio (bgm.wav, jump.wav, coin.wav, gameover.wav)

How to run:
1. Unzip and serve the folder with a static server:
   - `npx http-server` in the folder, then open `http://localhost:8080`
   - Or upload to GitHub Pages / Netlify

Notes:
- Environment lighting is simulated for a jungle feel (green rim light + warm key + bloom).
- If you want an actual HDRI, replace `scene.environment` setup and add an HDR file and use `RGBELoader` + `PMREMGenerator`.
