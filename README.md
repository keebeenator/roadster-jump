# Roadster Jump

Single-file HTML5 canvas game (no dependencies): jump the new Tesla Roadster over a line of parked Teslas: Model 3, Model Y, Tesla Semi, Cybertruck, Cybercab. Each level adds 2 more vehicles.

Play: https://keebeenator.github.io/roadster-jump/

## Controls
- **Hold** anywhere to accelerate (speedometer; the green arc is the speed you need). **Release** to stop throttling. If you release on the last part of the ramp you get a small "POP" hop. If you're still holding at the ramp lip, the car launches at its current speed.
- **In the air:** tap **Enable Motion**, hold the phone how you like to play, then tap **Calibrate**. Tilt to fire the nose or tail thrusters. Portrait: tilt left = nose up. Landscape: tilt the top edge. Tilt has a 12° dead zone, full effect at 55°, and exponential smoothing (α 0.15). The sensitivity slider is saved.
- **Fallback:** ▲/▼ on-screen thruster buttons, or Arrow keys (Space = throttle).
- Land wheels-down, close to the slope of the blue LAND ramp: within 8° is **Perfect**, up to 32° is **Rough**, anything else is a **Crash**.

URL modes: `?demo=air`, `?demo=result`.
