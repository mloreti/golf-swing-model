# Golf Swing Model

Interactive golf swing physics in a single HTML file: club delivery, ball flight, interactive lessons, an animated 3D swing with fault presets, swing-video analysis and a delivery optimizer.

**Live site:** https://mloreti.github.io/golf-swing-model/

## Tabs

- **Model** – set club delivery (speed, low point, plane, path, face, loft) and equipment/conditions; see the 3D swing plane, impact views and ball flight.
- **Learn** – short articles with interactive diagrams: attack angle, low point, swing plane, D-plane, dynamic loft, release and shaft lean, launch/spin window.
- **3D Swing** – kinematic 3D golfer with timeline scrubbing, orbit, body and club sliders, common-fault presets, compare view and force plate.
- **Analyze** – load one or two swing videos; scrub, draw, mark checkpoints, track the body and compare side by side.
- **Optimizer** – tune driver, 7i or SW delivery (loft, attack angle, path, face, speed, spin, strike location) and see the ball flight; find the best attack angle and loft.

## Running locally

Open `swing-model.html` in a browser, or serve the folder (`python3 -m http.server`) and visit `/swing-model.html`. No build step or dependencies.

Right- or left-handed golfer: use the toggle in the header.
