# HOLO//STACK

A 3D interface concept in a single file. A holographic device, the fictional "HX-6", plays through a 48-second cinematic loop. It breaks apart into six component layers, and a game-style HUD drives it.

Open `index.html` in a browser. There is no build step: three.js loads from jsDelivr and the fonts from Google Fonts.

## What's in it
- **Six decomposable layers**: chassis cage, circuit substrate (with pulses travelling along the traces), a noise-displaced flux core, data rings, a neural lattice, and a particle field. Each is its own scene group with live telemetry.
- **Cinematic camera**: six keyframed shots on a closed Catmull-Rom path, eased between beats, with lens and shot readouts. The layers break apart at 0:17 and reassemble at 0:38.
- **Callouts**: in the exploded view, each layer gets a label in one aligned column. The projection shifts with `setViewOffset` so the object moves aside to make room for them.
- **HUD**: compass tape, camera-path minimap, a timeline you can scrub, a hotbar, a layer inspector with render stats, and a cinema mode for clean screen recordings.
- **Post-processing**: bloom, chromatic aberration, scanlines, vignette and film grain.

## Controls
| Input | Action |
| --- | --- |
| Drag / scroll | Orbit and zoom (takes the camera; the cinematic resumes after 6 s idle) |
| W A S D, Q E | Fly |
| Space | Decompose / reassemble |
| 1–6, Shift+1–6 | Toggle / solo a layer |
| Tab | Layer inspector |
| C / Esc | Cinema mode on / off |
| R | Resume the cinematic |
| ← → | Scrub 1 s |
| P | Play / pause |
| H | Hide the HUD |

Tip for a LinkedIn clip: press **C**, then screen-record one full 48-second loop.
