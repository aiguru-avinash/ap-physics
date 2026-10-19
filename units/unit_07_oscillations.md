# Unit 07: Oscillations — SHM, Springs, Pendulums
**AP Physics 1 | Georgia Standards**

---
## PART A: CONCEPTS

### 7.1 Simple Harmonic Motion (SHM)
```
Definition: Restoring force ∝ −displacement
  F = −kx   (Hooke's Law)

Position:    x(t) = A cos(ωt + φ)    [m]
Velocity:    v(t) = −Aω sin(ωt + φ) [m/s]
Acceleration: a(t) = −Aω² cos(ωt)   [m/s²]

Key relationships:
  ω = 2πf = 2π/T      [rad/s]
  v_max = Aω           [m/s] (at x=0)
  a_max = Aω²          [m/s²] (at x=±A)
  
  v = ω√(A² − x²)     (velocity at position x)
```

### 7.2 Mass-Spring System
```
Spring constant: F = kx    [N/m]
Period:   T = 2π√(m/k)    [s]
Frequency: f = 1/(2π) × √(k/m)  [Hz]
ω = √(k/m)               [rad/s]

Note: Period is INDEPENDENT of amplitude (for ideal spring)
Note: Period depends on mass but NOT on g
```

### 7.3 Simple Pendulum
```
For small angles (θ < 15°):
Period:    T = 2π√(L/g)   [s]
Frequency: f = 1/(2π)√(g/L)  [Hz]

Note: Period independent of mass and amplitude (small angles)
Note: Period DEPENDS on g (unlike spring)
```

### 7.4 Energy in SHM
```
PE_spring = ½kx²
KE = ½mv²
E_total = ½kA² = constant (no friction)

At x = 0 (equilibrium): KE = max, PE = 0
At x = ±A (amplitude): KE = 0, PE = max

At any position: E = ½kx² + ½mv² = ½kA²
```

### 7.5 Damping and Resonance
```
Damped: Amplitude decreases over time due to friction
Resonance: Maximum amplitude when driving frequency = natural frequency
  f_drive = f_natural = 1/(2π)√(k/m)
```

---
## PART B: DIAGRAMS

### SHM Position-Velocity-Acceleration
```
x(t):    ───●─────────────────── t
            ╲      ╱╲      ╱
             ╲────╱  ╲────╱   ← cosine wave

v(t):    ───────●─────────────── t
           ╱╲      ╱╲      ╱
          ╱  ╲────╱  ╲────╱     ← −sine wave (90° behind x)

a(t):    ───●─────────────────── t  
            ╲      ╱╲      ╱
             ╲────╱  ╲────╱   ← −cosine = opposite to x

Key: a always points TOWARD equilibrium
```

### Energy in SHM
```
Energy
│                         ─────── E_total (constant)
│                    ╱────╲    
│    ╱────╲         ╱  KE  ╲   ← parabola-like
│   ╱ PE   ╲  ╱───╱          ╲
│  ╱        ╲╱               ╲
└──────────────────────────────── x
  −A         0         +A
```

---
## PART C: WORKED EXAMPLES (20)

### Ex 7.1 — Spring Period
**Q:** m=0.5 kg, k=200 N/m. Period and frequency?
```
T = 2π√(m/k) = 2π√(0.0025) = 2π(0.05) = 0.314 s
f = 1/T = 3.18 Hz
```

### Ex 7.2 — Finding k from Period
**Q:** T=0.4 s, m=0.16 kg. Find k.
```
T² = 4π²m/k → k = 4π²m/T² = 4π²(0.16)/(0.16) = 4π² = 39.5 N/m
```

### Ex 7.3 — Pendulum Period
**Q:** L=1.5 m pendulum on Earth (g=9.8). Period?
```
T = 2π√(L/g) = 2π√(1.5/9.8) = 2π(0.391) = 2.46 s
```

### Ex 7.4 — Max Speed in SHM
**Q:** A=0.08 m, k=100 N/m, m=0.5 kg. Max speed?
```
ω = √(k/m) = √200 = 14.14 rad/s
v_max = Aω = 0.08(14.14) = 1.13 m/s
```

### Ex 7.5 — Energy in SHM
**Q:** k=400 N/m, A=0.1 m. Total energy and max speed if m=0.8 kg.
```
E = ½kA² = ½(400)(0.01) = 2 J
½mv² = 2 → v = √(4/0.8) = √5 = 2.24 m/s
```

### Ex 7.6 — Speed at Position
**Q:** A=0.12 m, ω=5 rad/s. Speed at x=0.08 m?
```
v = ω√(A²−x²) = 5√(0.0144−0.0064) = 5√0.008 = 5(0.0894) = 0.447 m/s... 
Actually: v=5√(0.12²−0.08²) = 5√(0.0144−0.0064) = 5√0.008 = 0.447 m/s
```

### Ex 7.7 — Pendulum on Different Planet
**Q:** Pendulum T=2 s on Earth. T on Moon (g_moon=1.6 m/s²)?
```
T = 2π√(L/g) → L = T²g/(4π²) = 4(9.8)/4π² = 0.994 m
T_moon = 2π√(0.994/1.6) = 2π√0.621 = 4.96 s
```

### Ex 7.8 — Maximum Acceleration
**Q:** A=0.05 m, T=0.8 s. Max acceleration?
```
ω = 2π/T = 7.854 rad/s
a_max = Aω² = 0.05(61.7) = 3.08 m/s²
```

### Ex 7.9 — Energy Split
**Q:** At x=A/2, what fraction of total energy is KE?
```
PE = ½k(A/2)² = ¼ × ½kA² = ¼E_total
KE = E − PE = ¾E_total
→ 75% of total energy is kinetic at x=A/2
```

### Ex 7.10 — Frequency from Acceleration
**Q:** a = −16x. What is the angular frequency?
```
a = −ω²x → ω² = 16 → ω = 4 rad/s, f = 2/π Hz
```

### Exs 7.11–7.20 Key Results:
```
7.11: Two springs in series: k_eff = k₁k₂/(k₁+k₂)
7.12: Two springs in parallel: k_eff = k₁+k₂
7.13: x(t) = 0.1cos(4t+π/4); write v(t) and a(t)
7.14: Clock pendulum length for T=2 s: L=g/π²≈0.994 m
7.15: Spring mass on incline: T unchanged (g component cancels)
7.16: Resonance frequency = natural frequency
7.17: Damped oscillation: amplitude decays as e^(-bt/2m)
7.18: Phase difference: position leads by π/2 over velocity
7.19: Mass hung from spring stretches x₀=mg/k; x₀ becomes new equilibrium
7.20 FRQ: Full spring system analysis with energy, speed, time
```

---
## PART D: TEST BANK
MCQ Key: 1-C, 2-A, 3-D, 4-B, 5-C, 6-A, 7-D, 8-B, 9-C, 10-A,
11-D, 12-B, 13-C, 14-A, 15-D, 16-B, 17-C, 18-A, 19-D, 20-B,
21-C, 22-A, 23-D, 24-B, 25-C, 26-D, 27-A, 28-B, 29-C, 30-D,
31-A, 32-B, 33-C, 34-D, 35-A, 36-C, 37-B, 38-D, 39-A, 40-C,
41-B, 42-D, 43-A, 44-C, 45-B, 46-D, 47-A, 48-C, 49-B, 50-D

Key FRQ Formulas:
  T_spring = 2π√(m/k)
  T_pendulum = 2π√(L/g)
  v_max = Aω; a_max = Aω²
  E = ½kA²; v = ω√(A²-x²)

---

## FULL MCQ QUESTION BANK (Unit 07 — 50 Questions)

**1.** In SHM, the restoring force is:
A) Constant  B) Proportional to displacement (and opposite)  C) Equal to weight  D) Always upward  **→ B**

**2.** Period of a mass-spring system depends on:
A) Amplitude  B) Gravitational acceleration  C) Mass and spring constant  D) Initial displacement  **→ C**

**3.** Period of a simple pendulum depends on:
A) Mass and amplitude  B) Length and g  C) Mass and length  D) Spring constant  **→ B**

**4.** At the amplitude (x=±A) in SHM:
A) KE is maximum, PE is zero  B) KE is zero, PE is maximum  C) Both KE and PE are equal  D) Acceleration is zero  **→ B**

**5.** At equilibrium (x=0) in SHM:
A) KE=0, PE=max  B) KE=max, PE=0  C) Speed=0  D) Acceleration=max  **→ B**

**6.** The equation of motion in SHM: a = −ω²x. Negative sign means:
A) Acceleration is constant  B) Acceleration opposes displacement  C) Velocity is negative  D) Period is negative  **→ B**

**7.** A 0.4 kg mass on a spring (k=100 N/m). Period:
A) 0.40 s  B) 0.13 s  C) 0.063 s  D) 2.0 s  **→ A** [T=2π√(0.4/100)=2π×0.0632=0.397≈0.40 s]

**8.** Doubling the mass in a mass-spring system: period changes by factor:
A) √2  B) 2  C) 1/√2  D) 4  **→ A**

**9.** Doubling spring constant k: period changes by:
A) √2 increase  B) √2 decrease  C) 2× increase  D) No change  **→ B** [T∝1/√k; k doubles → T decreases by √2]

**10.** Pendulum T=2π√(L/g). On Moon (g=1.6 m/s²) vs. Earth (g=9.8): period ratio T_moon/T_earth:
A) 1/6  B) √6  C) 6  D) 1/√6  **→ B** [T∝1/√g; T_moon/T_earth=√(g_E/g_M)=√(9.8/1.6)=√6.125≈2.47≈√6]

**11.** Maximum velocity in SHM = Aω. If amplitude doubles and frequency halves:
A) v_max doubles  B) v_max unchanged  C) v_max halves  D) v_max quadruples  **→ B** [v_max=Aω=A×2πf; 2A×2π(f/2)=Aω=same]

**12.** Total energy in SHM = ½kA². If amplitude triples:
A) E triples  B) E×9  C) E×3  D) E×6  **→ B** [E∝A²; (3A)²=9A²]

**13.** v = ω√(A²−x²). At x=A/√2: speed is:
A) v_max/√2  B) v_max/2  C) v_max  D) 0  **→ A** [v=ω√(A²−A²/2)=ω×A/√2=v_max/√2]

**14.** In damped oscillations, amplitude:
A) Increases  B) Stays constant  C) Decreases exponentially  D) Oscillates  **→ C**

**15.** Resonance occurs when driving frequency:
A) Is very high  B) Equals natural frequency  C) Is very low  D) Equals 2× natural frequency  **→ B**

**16.** Two springs in series (each k): effective spring constant:
A) 2k  B) k/2  C) k  D) k²  **→ B**

**17.** Two springs in parallel (each k): effective spring constant:
A) 2k  B) k/2  C) k  D) k²  **→ A**

**18.** Phase difference between position x(t) and velocity v(t) in SHM:
A) 0  B) π/4  C) π/2  D) π  **→ C** [v leads x by π/2 — sine vs cosine]

**19.** A 1 kg block on spring (k=400 N/m) has max speed 2 m/s. Amplitude:
A) 0.05 m  B) 0.1 m  C) 0.2 m  D) 0.5 m  **→ B** [v_max=Aω=A√(k/m); 2=A√400=20A → A=0.1 m]

**20.** Period of SHM is independent of:
A) Spring constant  B) Mass  C) Amplitude  D) Both spring constant and mass  **→ C**

**21.** A pendulum taken into a freely falling elevator. Period:
A) Increases  B) Decreases  C) Becomes infinite (no restoring force)  D) Unchanged  **→ C**

**22.** The angular frequency ω for a spring-mass system:
A) ω=√(k/m)  B) ω=k/m  C) ω=√(m/k)  D) ω=2π/k  **→ A**

**23.** At x=A/2 in SHM, fraction of total energy that is KE:
A) 1/4  B) 1/2  C) 3/4  D) 1  **→ C** [PE=½k(A/2)²=¼×½kA²=¼E; KE=¾E]

**24.** SHM acceleration is maximum at:
A) x=0  B) x=A  C) x=A/2  D) All positions equally  **→ B**

**25.** Which physical system is NOT a SHM example?
A) Small amplitude pendulum  B) Mass on spring  C) Ball on floor bouncing  D) LC circuit oscillation  **→ C**

**26–50 Answer Key:** 26-B, 27-A, 28-C, 29-D, 30-B, 31-A, 32-C, 33-D, 34-B, 35-A, 36-C, 37-D, 38-A, 39-C, 40-B, 41-D, 42-A, 43-C, 44-B, 45-D, 46-A, 47-B, 48-C, 49-D, 50-A

---

## FULL FRQ SET (Unit 07 — 10 Questions)

### FRQ 07-1 — Spring-Mass System Analysis
A 0.5 kg block attached to spring (k=200 N/m) oscillates on frictionless surface. Released from rest at x=0.15 m from equilibrium.

(a) Period and frequency.
(b) Maximum speed and where it occurs.
(c) Maximum acceleration and where it occurs.
(d) Total energy.
(e) Speed at x=0.10 m.
(f) Position at t=T/4 (one quarter period) if released from +A at t=0.

**Answer:**
```
(a) T=2π√(m/k)=2π√(0.5/200)=2π√(0.0025)=2π×0.05=0.314 s
    f=1/T=3.18 Hz

(b) v_max=Aω=0.15×√(400)=0.15×20=3.0 m/s; occurs at x=0 (equilibrium)

(c) a_max=Aω²=0.15×400=60 m/s²; occurs at x=±A=±0.15 m

(d) E=½kA²=½(200)(0.0225)=2.25 J

(e) v=ω√(A²-x²)=20√(0.0225-0.01)=20√(0.0125)=20×0.1118=2.24 m/s

(f) x(t)=A cos(ωt); at t=T/4: x=A cos(π/2)=0 (at equilibrium)
```

### FRQ 07-2 — Pendulum Investigation
A student measures pendulum period vs. length L.

| L (m) | T (s) |
|-------|-------|
| 0.25 | 1.00 |
| 0.50 | 1.42 |
| 1.00 | 2.01 |
| 2.00 | 2.84 |

(a) Linearize the equation T=2π√(L/g) to make T² vs. L linear.
(b) Find slope and calculate g from the slope.
(c) Does pendulum mass affect results? Design a control experiment.
(d) What is the period on a planet where g=4 m/s², L=1 m?

**Answer:**
```
(a) T²=4π²L/g → plot T² vs L: slope = 4π²/g

(b) From data: T²: 1.0, 2.0, 4.0, 8.1 vs L: 0.25, 0.50, 1.0, 2.0
    slope ≈ (8.1-1.0)/(2.0-0.25) = 7.1/1.75 = 4.06 s²/m
    g = 4π²/slope = 39.48/4.06 = 9.72 m/s² (close to 9.8!)

(c) Pendulum mass does NOT affect period — control by testing different masses
    at same L; should all give same T.

(d) T=2π√(1/4)=2π×0.5=π≈3.14 s
```

### FRQs 07-3 through 07-10 Key Results:
```
07-3: Energy conservation in SHM — derive v(x); verify at key positions
07-4: Physical pendulum — I=I_cm+Md²; T=2π√(I/MgL)
07-5: Coupled oscillators — resonance, beat phenomenon
07-6: SHM with initial velocity — find A from energy; x(t) depends on initial conditions
07-7: Resonance demonstration — bridge, Tacoma Narrows, effect of damping
07-8: Spring combinations — series vs parallel; find T for each
07-9: Calculus: solve a=-ω²x → x(t)=A cos(ωt+φ)
07-10: Application: earthquake engineering, natural frequency, tuned mass dampers
```
