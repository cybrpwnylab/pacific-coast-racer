# Pacific Coast Racer

A pseudo-3D arcade racer in the browser, in the spirit of 90s arcade driving games, with soft N64-era visuals. One car, one track, one race.

You drive a white mid-engine sports car (an MR2-style coupe) down a fictional run of California State Route 1 against five rivals and a road full of slower traffic.

## How to play

Open `index.html` in a browser, then press **Space**.

- **← / →** (or A / D): steer. **M** mutes the sound. The car accelerates on its own; there is no brake.
- Curves push you toward the outside, so keep steering into them.
- Leaving the pavement slows you down. Hitting roadside trees and rocks nearly stops you. Bumping a rival or a traffic car costs a lot of speed, so weave through the traffic cleanly.
- Cross the finish line in the best position you can. Your best time is saved in the browser.
- Touch: hold the left or right half of the screen.

## The track

Malibu beach palms, the Big Sur coast (cypress, cliffs, a lighthouse), a redwood grove, then the Carmel coast to the finish.

## Tech

Single file: HTML canvas, no dependencies, no audio files.

- **Graphics:** the road is drawn with the classic segment-projection technique at 960x600 with smooth shading, distance fog, a gradient sky with parallax mountains, and vector-drawn cars.
- **Sound:** everything is synthesized with the Web Audio API: a revving engine with gear shifts, wind and off-road rumble, crash sounds, countdown beeps and an arcade-style music loop. Sound starts after your first key press.
