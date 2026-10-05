# Project Meridian

An interdimensional gate simulator. Travel between 45 alternate Earths, read the scientists' field reports, and watch the danger meter.

## Run it
Open `index.html` in a browser. Keep `style.css`, `script.js` and `textures.js` in the same folder. `meridian-standalone.html` is the same game in a single file.

## Controls
- Drag the globe to spin it. It also turns slowly on its own.
- Hover the blinking point, then click it to read the field report.
- Press **D**, or hold the globe, to open the gate dial. Esc or Close leaves it.
- Press **J** for the field journal (reports you have read, notebook codes, achievements, endings).
- In the gate dial, the chips at the bottom filter gates: not visited, danger 6+, locked.
- Press **M** for the Multiverse Web. **Mix** sets master, ambience and effects volume.

- **Mix** panel: volume (master, ambience, effects, music), calm mode, large text, high contrast, vibration (Android only). Pinch or scroll the globe to zoom; double-click resets.

- The globe is drawn on your graphics card (WebGL). If your device is slow or has no WebGL, it switches to the older software renderer by itself. Add `?cpu` to the address, or untick "GPU rendering" in the Mix panel, to force the software renderer.

## Notes
- Lowering the danger reading: visit calm Earths (hazard 2 or less) for the first time, or use **Coil calibration** in the Home Earth report (4 uses in total, 2 jumps apart).
- Weather matters: in storms the recordings are garbled (wait for a lull), mistakes cost more and leaving adds turbulence; under clear skies encounters are more forgiving.
- After an ending, a new expedition keeps some bonuses (extra recalibrations, hardened coils, an old notebook code). There are hidden things to find.
- First-time tips appear on a new game; "Skip tips" turns them off.
- Sealed gates need a 4-digit code found in other reports (your notebook records them). Forbidden gates need enough Earths logged.
- Every Earth has its own weather simulated with simple physics (gravity, drag, wind gusts, bounce, drifting snow and ash).
- Push the danger meter into the red and the gate will warn you, then fail. There are two endings. Progress is saved in your browser.
- The picture renders at your screen's native resolution (up to 1.5x on the globe) and lowers itself automatically if your device is slow.

## Files
`index.html` page · `style.css` styling · `script.js` game logic · `textures.js` planet maps (base64)
