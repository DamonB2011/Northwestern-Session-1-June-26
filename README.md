# Northwestern-Session-1-June-26

I built these models during a session at Northwestern, working under real aerodynamic constraints instead of just theory. The wing had to perform under subsonic conditions. I ran four iterations, each one testing a different balance of camber, chord, and sweep, until I found a version that actually held up. Bubbledancer worked. It's the only one I took from SolidWorks to a printed, physical wing. All the IMG files are photos of my works.

# Wing Design — SolidWorks

> NOTE: I filled every bracket below with AI-guessed placeholder content so you can see what a finished doc looks like. None of the numbers or design decisions here are real. Replace all of it with what actually happened.

## Overview

I designed four wing iterations in SolidWorks for an aerospace engineering project at Northwestern. Each one tested how leading edge, trailing edge, camber, chord line, mean camber line, sweep angle, and angle of attack affect performance. I 3D printed the final design, Bubbledancer, into a working wing model.

I set out to optimize for subsonic flight, balancing lift-to-drag ratio against a set of speed and structural constraints. Each iteration tested a different combination of camber and sweep angle so I could see how the tradeoffs played out in practice, not just on paper.

## Design Iterations

### Wing 1
I started with a symmetric, low-camber airfoil and a straight, zero-degree sweep angle. Close to a basic reference profile, nothing optimized yet.

**Problem:** It generated lift, but the lift-to-drag ratio was poor at the target speed. Too much drag for the lift it produced.

### Wing 2
I increased camber to boost lift and left the sweep angle unchanged.

**Problem:** Lift improved, but drag increased even more. Camber alone wasn't the fix.

### Wing 3
I introduced a moderate sweep angle to cut drag and kept the higher camber from Wing 2.

**Problem:** Drag dropped, but the combination shifted the mean camber line enough to make the wing unstable at the target angle of attack.

### Wing 4 - Bubbledancer (Final)
I brought the camber back down slightly, kept the swept design, and adjusted the chord line to restore stability at the design angle of attack.

**Why it worked:** The slightly lower camber kept the drag reduction from Wing 3. The adjusted mean camber line restored a stable lift distribution at the intended angle of attack. Together they gave me the best lift-to-drag balance of the four.

## Technical Specs (Bubbledancer)

| Property | Value |
|---|---|
| Airfoil profile | NACA 2412-style, modified |
| Chord length | 80 mm |
| Sweep angle | 15° |
| Angle of attack (design) | 5° |
| Camber | 2% |
| Material (print) | PLA |

## Fabrication

I 3D printed the final SolidWorks model in PLA, then checked the fit and inspected the leading edge for warping before final assembly.

## Key Concepts Applied

- **Leading edge / trailing edge**: The leading edge shape controlled how cleanly air split around the wing. Trailing edge sharpness controlled how efficiently airflow rejoined behind it.
- **Camber / mean camber line**: Camber controlled how much lift the wing generated. I used the mean camber line to compare curvature across iterations.
- **Chord line**: My baseline reference for measuring angle of attack and keeping proportions consistent across iterations.
- **Sweep angle**: I adjusted this to manage drag at the target speed, trading off against stability.
- **Angle of attack**: The design condition each iteration was built around. Any change elsewhere in the wing had to stay stable at this angle.
