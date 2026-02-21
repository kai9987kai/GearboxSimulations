# GearboxSimulations

A small collection of **browser-based gearbox / powertrain simulation pages** (single-file `.html` documents) focused on **geartrain kinematics, torque multiplication, stress/thermal “bloom” visualization concepts, and transmission power-flow logic**.

The repo currently contains five simulations you can run by simply opening the HTML files in any modern browser. :contentReference[oaicite:0]{index=0}

---

## What’s inside

### 1) `Simulation1.html` — Ultra-Realistic Miniature Gearbox Simulation
A compact gearbox telemetry concept with live readouts for:
- Motor input RPM
- Output speed
- Gear ratio (shown as `1:9`)
- Torque multiplier (shown as `9.00x`) :contentReference[oaicite:1]{index=1}

### 2) `Simulation2-DynamicFEA.html` — Dynamic FEA Gearbox
A real-time “Dynamic FEA” style page framing **structural stress visualization** at gear mesh points, with a **Von Mises stress** legend (low/med/high). :contentReference[oaicite:2]{index=2}

### 3) `Simulation3-heavylift.html` — Heavy Lift Simulator (2-Stage System)
A heavy-lift traction hoist concept describing:
- 2-stage planetary + parallel reduction
- AC induction motor context
- Output torque, payload, motor temperature, peak stress (VM), factor-of-safety messaging
- Stress/strain “bloom” scale (yield/fracture) :contentReference[oaicite:3]{index=3}

### 4) `simulation4-wormdrive.html` — Worm Drive & Conveyor (40:1)
An industrial worm drive scenario focused on:
- High ratio torque multiplication (40:1)
- Self-locking behavior tradeoffs
- Sliding friction + heat at the contact point
- Efficiency, friction temperature, lubrication state, thermal critical thresholds :contentReference[oaicite:4]{index=4}

### 5) `Simulation5-asynchronousclutch.html` — Asynchronous Dual-Clutch (DCT)
A DCT (dual-clutch transmission) logic explainer showing:
- Two power shafts (odd/even gear separation)
- Asynchronous pre-selection of the next gear
- “Active power flow” / clutch state and RPM readouts :contentReference[oaicite:5]{index=5}

---

## Quick start (local)

### Option A — Just open the files
1. Download / clone the repo:
   ```bash
   git clone https://github.com/kai9987kai/GearboxSimulations.git
   cd GearboxSimulations
````

2. Double-click any of the `.html` files (or right-click → “Open with” → your browser). ([GitHub][1])

### Option B — Run a local web server (recommended)

Some browsers restrict certain features when opening files via `file://`. A local server avoids that.

**Python (cross-platform):**

```bash
python -m http.server 8000
```

Then open:

* `http://localhost:8000/Simulation1.html`
* `http://localhost:8000/Simulation2-DynamicFEA.html`
* `http://localhost:8000/Simulation3-heavylift.html`
* `http://localhost:8000/simulation4-wormdrive.html`
* `http://localhost:8000/Simulation5-asynchronousclutch.html` ([GitHub][1])

---

## Project structure

```
GearboxSimulations/
  LICENSE
  Simulation1.html
  Simulation2-DynamicFEA.html
  Simulation3-heavylift.html
  simulation4-wormdrive.html
  Simulation5-asynchronousclutch.html
```

([GitHub][1])

---

## Goals / scope

* Provide **interactive, readable “engineering UI” style** simulation pages.
* Emphasize **gear ratio → torque multiplication**, plus high-level **stress/thermal** intuition.
* Stay **dependency-light** (single HTML pages you can share easily). ([GitHub][1])

---

## License

Apache License 2.0. See `LICENSE`. ([GitHub][1])

---

## Author

Kai Piper ([@kai9987kai](https://github.com/kai9987kai))

```
::contentReference[oaicite:11]{index=11}
```

[1]: https://github.com/kai9987kai/GearboxSimulations "GitHub - kai9987kai/GearboxSimulations"
