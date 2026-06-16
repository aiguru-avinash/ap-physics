# AP Physics — Curriculum & Study Database
### Georgia Standards · College Board CED aligned

Complete AP Physics curriculum (AP1, AP2, and AP C material where applicable).
This repository mirrors the content from the `APPhysics.html` site: concise unit blueprints,
diagram systems, worked examples, MCQs, and FRQs for classroom and self-study use.

Key stats (from the site):
- Units: 15
- Worked examples: 300+
- Multiple-choice questions (MCQ): 750+
- Free-response questions (FRQ): 150+

---

## Quick project layout

All core content lives in the `units/` folder as Markdown files. The site HTML (`APPhysics.html`) is a single-page view built from the same source material.

```
ap-physics/
├── APPhysics.html        ← single-page site (visual curriculum viewer)
├── README.md             ← this file
├── units/                ← per-unit Markdown (content source)
│   ├── unit_01_kinematics.md
│   ├── unit_02_dynamics.md
│   ├── unit_03_work_energy_power.md
│   └── ... (units 04–15)
```

---

## Units (15) — short summaries

01 — Kinematics
  - 1D & 2D motion, projectile motion, SUVAT equations, graphs (x–t, v–t), calculus connections.

02 — Force & Dynamics
  - Newton's laws, free-body diagrams, friction, normal force, inclines, Atwood systems.

03 — Work, Energy & Power
  - Work (dot product), KE, PE (gravity & spring), conservation of energy, power (P = F·v).

04 — Linear Momentum
  - Impulse, momentum conservation, elastic & inelastic collisions, center of mass.

05 — Rotational Dynamics
  - Torque, moment of inertia, rotational equilibrium, rigid-body rotation.

06 — Rotating Systems (Energy & Momentum)
  - Angular momentum, rolling motion, energy in rotating systems (AP C overlap).

07 — Oscillations & SHM
  - Simple harmonic motion, springs, pendulums, resonance, damping basics.

08 — Fluids
  - Pressure, buoyancy, Bernoulli, continuity equation, fluid statics & dynamics.

09 — Thermodynamics
  - PV diagrams, work in thermodynamic processes, heat engines, Carnot efficiency.

10 — Electrostatics
  - Coulomb's law, electric field, potential, capacitors.

11 — Electric Circuits
  - Ohm's law, Kirchhoff's rules, RC circuits, power in circuits.

12 — Magnetism
  - Magnetic fields, forces on charges and currents, Faraday's law, induction.

13 — Geometric Optics
  - Reflection, refraction, lenses and mirrors, Snell's law, ray tracing.

14 — Waves & Sound
  - Wave kinematics, interference, Doppler effect, diffraction and resonance.

15 — Modern Physics
  - Photoelectric effect, Bohr model, basics of quantum and nuclear phenomena.

---

## How to use

- To read the nicely formatted single-page view, open `APPhysics.html` in a browser.
- To edit or extend content, update the Markdown files under `units/`.
- Each unit file follows the pattern: Part A (concepts), Part B (diagrams), Part C (worked examples), Part D (test bank & FRQs).
- The Markdown files are standalone and intended for easy export to other formats or site builds.

---

## Contributing

- Add or improve worked examples and FRQs in the corresponding `units/unit_XX_*.md`.
- Keep answers and derivations clear and show units. Prefer step-by-step solutions for student use.
- If you modify `APPhysics.html`, ensure any generated snippets remain in sync with the `units/` sources.

---

## License & attribution

This content was assembled for educational use. If you plan public redistribution or reuse, please include proper attribution to the original author/source where applicable.
