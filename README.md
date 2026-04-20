
# GearboxSimulations

A small collection of browser-based gearbox and powertrain simulation pages focused on geartrain kinematics, torque multiplication, stress/thermal visualisation concepts, and transmission power-flow logic.

Each simulation is a single-file HTML document and can be run directly in a modern browser with no build step and no external dependencies.

---

## What’s inside

### `Simulation1.html` — Ultra-Realistic Miniature Gearbox Simulation
A compact gearbox telemetry concept with live readouts for:
- Motor input RPM
- Output speed
- Gear ratio
- Torque multiplication

### `Simulation2-DynamicFEA.html` — Dynamic FEA Gearbox
A real-time “Dynamic FEA” style page that visualises structural stress at gear mesh points, including:
- Von Mises stress mapping
- Low / medium / high stress zones
- Engineering-style diagnostic display

### `Simulation3-heavylift.html` — Heavy Lift Simulator (2-Stage System)
A heavy-lift traction hoist concept describing:
- 2-stage planetary + parallel reduction
- AC induction motor context
- Output torque and payload logic
- Motor temperature, peak stress, and factor-of-safety indicators
- Stress / strain “bloom” scale from yield to fracture

### `simulation4-wormdrive.html` — Worm Drive & Conveyor (40:1)
An industrial worm drive scenario focused on:
- High-ratio torque multiplication
- Self-locking behaviour tradeoffs
- Sliding friction and heat at the contact point
- Efficiency, lubrication, and thermal threshold logic

### `Simulation5-asynchronousclutch.html` — Asynchronous Dual-Clutch (DCT)
A dual-clutch transmission logic explainer showing:
- Odd/even gear power shafts
- Asynchronous pre-selection of the next gear
- Active power flow states
- Clutch and RPM readouts

### `Simulation6.html` — Contactless Magnetic Gearbox Prototype
A next-generation experimental drivetrain simulation focused on:
- Magnetic / contactless torque transfer
- Reduced mechanical wear compared to direct tooth engagement
- Variable coupling strength under load
- Efficiency mapping across different gap distances
- Thermal and slip-loss behaviour
- Torque smoothing under fluctuating input conditions
- Conceptual UI for comparing mechanical and non-contact drive architectures

---

## Quick start

### Option 1: Open directly
1. Clone the repository:
   ```bash
   git clone https://github.com/kai9987kai/GearboxSimulations.git
   cd GearboxSimulations
````

2. Open any `.html` file in your browser.

### Option 2: Run a local server

This is recommended if your browser restricts local file behaviour.

```bash
python -m http.server 8000
```

Then open one of these URLs:

* `http://localhost:8000/Simulation1.html`
* `http://localhost:8000/Simulation2-DynamicFEA.html`
* `http://localhost:8000/Simulation3-heavylift.html`
* `http://localhost:8000/simulation4-wormdrive.html`
* `http://localhost:8000/Simulation5-asynchronousclutch.html`
* `http://localhost:8000/Simulation6.html`

---

## Project structure

```text
GearboxSimulations/
  LICENSE
  README.md
  Simulation1.html
  Simulation2-DynamicFEA.html
  Simulation3-heavylift.html
  simulation4-wormdrive.html
  Simulation5-asynchronousclutch.html
  Simulation6.html
```

---

## Design goals

* Present gearbox and drivetrain concepts in a visual, readable way
* Demonstrate torque multiplication and gear ratio behaviour
* Communicate stress and thermal intuition through UI-style simulation pages
* Explore both conventional and experimental drivetrain architectures
* Stay dependency-light and easy to share

---

## Notes

These pages are concept simulations and educational visualisations rather than full engineering-grade solvers. They are intended for interactive demonstration, experimentation, and presentation.

---

## License

Licensed under the Apache License 2.0. See `LICENSE` for details.

---

## Author

Kai Piper
GitHub: [@kai9987kai](https://github.com/kai9987kai)

```

If you want, I can also :contentReference[oaicite:2]{index=2}.
::contentReference[oaicite:1]{index=1}
```
