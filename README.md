# Pacific Coast Racer

A pixel-art, pseudo-3D arcade racer in the browser, in the style of 80s/90s arcade driving games. One car, one track, one race.

You drive a white mid-engine sports car (an MR2-style coupe) down a fictional run of California State Route 1 against five rivals.

## How to play

Open `index.html` in a browser, then press **Space**.

- **← / →** (or A / D): steer. The car accelerates on its own; there is no brake.
- Curves push you toward the outside, so keep steering into them.
- Leaving the pavement slows you down. Hitting roadside trees and rocks nearly stops you. Bumping a rival costs speed.
- Cross the finish line in the best position you can. Your best time is saved in the browser.
- Touch: hold the left or right half of the screen.

## The track

Malibu beach palms, the Big Sur coast (cypress, cliffs, a lighthouse), a redwood grove, then the Carmel coast to the finish.

## Tech

Single file: HTML canvas, no dependencies. The game renders at 320x200 and is scaled up with pixelated filtering for the retro look. The road is drawn with the classic segment-projection technique.
