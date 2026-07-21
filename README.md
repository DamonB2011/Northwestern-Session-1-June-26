# Northwestern-Session-1-June-26

<p float="left">
  <img src="3D Improved Plane 1.jpeg" width="45%" />
  <img src="3D Improved Wing 1.jpeg" width="45%" />
</p>
<p float="left">
  <img src="Wings 3D 3.jpeg" width="45%" />
  <img src="Solidworks Photo 1.jpeg" width="45%" />
</p>

I built these models during a session at Northwestern, working under real aerodynamic constraints instead of just theory. The wing had to hold up under subsonic conditions, so I ran four iterations, each one testing a different balance of camber, chord, and sweep, until I landed on something that actually worked.

Bubbledancer was that version. It's the only one I took all the way from SolidWorks to a printed, physical wing. All the IMG files here are photos from the actual build.

## Wing Design - SolidWorks

### Overview

I designed four wing iterations in SolidWorks for an aerospace engineering project at Northwestern. Each one tested how leading edge, trailing edge, camber, chord line, mean camber line, sweep angle, and angle of attack affect performance.

I ended up 3D printing the final design, Bubbledancer, into a working wing model.

The goal was subsonic flight, balancing lift-to-drag ratio against a set of speed and structural constraints. Every iteration tried a different combination of camber and sweep so I could actually see how the tradeoffs played out, not just read about them.

### Design Iterations

#### Wing 1
Started simple: a symmetric, low-camber airfoil, straight zero-degree sweep. Basically a baseline reference profile, nothing optimized yet.
**Problem:** It made lift, but the lift-to-drag ratio was bad at the target speed. Too much drag for what it was producing.

#### Wing 2
Bumped up the camber to get more lift, left the sweep angle alone.
**Problem:** Lift got better, but drag went up even more. Camber alone wasn't the answer.

#### Wing 3
Added a moderate sweep to cut drag, kept the higher camber from Wing 2.
**Problem:** Drag dropped like I wanted, but the combination pushed the mean camber line far enough that the wing got unstable at the target angle of attack.

#### Wing 4 - Bubbledancer (Final)
Brought the camber back down a bit, kept the sweep, adjusted the chord line to get stability back at the design angle of attack.
**Why it worked:** The lower camber kept the drag reduction from Wing 3. The adjusted mean camber line gave me a stable lift distribution again. Between the two, this was the best lift-to-drag balance out of all four.

### Post-Test Redesign

Bubbledancer flew, but it broke during testing. Instead of treating that as the end of it, I used it as information. Back into SolidWorks, refined the camber and lift-to-drag ratio further, adjusted the sweep angle again, switched to stronger print material, and redesigned the winglets for better stability. The photos at the top of this README (the "Improved" ones) are that second-generation build, physically tougher and aerodynamically tighter than the original.

The other wing/glider files in here, Bubble Glider, Conscendo, Radian, and Reverse, are earlier prototypes I designed and tested in SolidWorks but never actually printed. Same design process, just exploring different camber, sweep, and structural approaches before I landed on the Bubbledancer line.

### Technical Specs (Bubbledancer)

| Property | Value |
|---|---|
| Airfoil profile | NACA 2412-style, modified |
| Chord length | 80 mm |
| Sweep angle | 15 |
| Angle of attack (design) | 5 |
| Camber | 2% |
| Material (print) | PLA |

### Fabrication

I printed the final SolidWorks model in PLA, checked the fit, and inspected the leading edge for warping before final assembly. After Bubbledancer broke in testing, I reprinted the improved version in a stronger material so it could actually hold up under the same conditions.

### Key Concepts Applied

- **Leading edge / trailing edge:** The leading edge shape controls how cleanly air splits around the wing. Trailing edge sharpness controls how efficiently airflow rejoins behind it.
- **Camber / mean camber line:** Camber controls how much lift the wing makes. I used the mean camber line to compare curvature across iterations.
- **Chord line:** My baseline reference for measuring angle of attack and keeping proportions consistent across versions.
- **Sweep angle:** Adjusted to manage drag at the target speed, trading off against stability.
- **Angle of attack:** The design condition every iteration had to stay stable at, no matter what else changed.

## Program Context

Outside of the SolidWorks work, the Northwestern session included talks with people actually working in aerospace. I got to interview a SpaceX and Boeing employee about their work in the industry, photo's included in this repo.

## Files in This Repo

- `AG25 Bubble Dancer DLG_Damon.SLDPRT` — final Bubbledancer SolidWorks part file
- `Bubble Glider Left/Right.SLDPRT`, `Conscendo_Left/Right.SLDPRT`, `Radian_Left/Right.SLDPRT`, `Reverse_Left/Right.SLDPRT` — earlier prototype wing/glider variants, designed but not printed
- `Wings 3D 1-3.jpeg`, `Solidworks Photo 1-3.jpeg` — SolidWorks renders and design process photos
- `3D Improved Wing 1-4.jpeg`, `3D Improved Plane 1.jpeg` — the rebuilt, post-test version of Bubbledancer
- `Workshop Pic 1-2.jpeg`, `Class Photo.jpeg` — program photos
- `Interview (SpaceX and Boeing Worker from NW Uni).jpeg` — from my interview with an aerospace industry professional during the program
- `IMG_4639.MOV`, `IMG_4640.MOV` — video footage
- `AG25 Bubble DancerDamon_project_folders.html` — project folder export
