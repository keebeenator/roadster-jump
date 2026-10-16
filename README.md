# Roadster Jump

Single-file HTML5 canvas game (no dependencies): jump the new Tesla Roadster over a line of parked Teslas: Model 3, Model Y, Tesla Semi, Cybertruck, Cybercab (drawn head-on, in a more realistic shaded 2D canvas style). The airborne phase runs in 0.35x slow motion. Each level adds 2 more vehicles.

Play: https://keebeenator.github.io/roadster-jump/

## Controls
- **Hold** anywhere to accelerate on flat ground (the green arc on the speedometer is the speed you need). **Release** to blast straight up on the thrusters; your run speed carries you over the fleet. Holding past the LIFT-OFF line launches you automatically.
- **In the air:** tap **Enable Motion**, hold the phone how you like to play, then tap **Calibrate**. Tilt to fire the nose or tail thrusters. Portrait: tilt left = nose up. Landscape: tilt the top edge. Tilt has a 12° dead zone, full effect at 55°, and exponential smoothing (α 0.15). The sensitivity slider is saved.
- **Restart level:** ↻ button top-right, "Restart level" on the result card, or the R key.
- **Fallback:** ▲/▼ on-screen thruster buttons, or Arrow keys (Space = throttle).
- Land wheels-down, near level on the ground past the fleet: within 8° is **Perfect**, up to 32° is **Rough**, anything else is a **Crash**.

URL modes: `?demo=air`, `?demo=result`.
