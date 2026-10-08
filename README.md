# HVDC LCC Operating-Point Simulator

Interactive, browser-based simulator of a High-Voltage Direct Current (HVDC) link based on
Line-Commutated Converters (LCC). It computes and visualises the steady-state operating point
from the converters' control characteristics and updates it in real time as you change the
controls and system parameters.

**Live demo:** https://202201844-del.github.io/hvdc-interactive/

## Features
- **V–I control diagram** with the classic HVDC characteristics — rectifier Constant Ignition
  Angle (CIA, α_min), inverter Constant Extinction Angle (CEA, γ0) and constant-current
  segments; the operating point is their intersection.
- **Bidirectional power flow** (Side 1 → 2 or 2 → 1) with current-margin control.
- **Interactive controls:** current order (Idref), minimum firing angle α_min, extinction
  angle γ0 and grid voltages (pu).
- **System design parameters:** DC voltage, DC cable resistance, AC grid voltages,
  converter-transformer reactance and rating, number of 6-pulse bridges, frequency and
  current margin.
- **Live single-line diagram** with on-diagram values, firing/extinction waveforms and
  per-converter results (mode, Vd, Id, active/reactive power).
- Responsive layout with light/dark theme. No build step and no external dependencies.

## How to run
- **Online:** open the live demo link above.
- **Locally:** download and open `index.html` in any modern browser — no installation required.

## Tech
Single self-contained file: vanilla HTML, CSS and JavaScript with inline SVG for the plots.

## Author
Favio Vargas Camacho — Electrical Engineering, Universidad Mayor de San Simón (Bolivia)
LinkedIn: https://www.linkedin.com/in/favio-vargas
