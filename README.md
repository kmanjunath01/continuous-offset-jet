# Thermal Mixing in Turbulent Offset Jet Flow

## Overview

This repository contains an OpenFOAM simulation of a two-dimensional turbulent offset jet with passive scalar heat transfer. The objective is to investigate the influence of offset ratio and turbulence on downstream thermal mixing and validate the numerical model against published experimental measurements.

---

## Problem Description

- Geometry: 2D offset jet
- Offset Ratio (OR): 7
- Reynolds Number: 15000
- Jet Width: h = 1

---

## Numerical Setup

Solver
- rhoPimpleFoam

Turbulence Model
- Standard k–ε

Density Model
- rhoConst

Heat Transfer
- Energy equation solved as a passive scalar.

Mesh
- Structured mesh (~45,000 cells)

---

## Validation

The numerical model was validated against the experimental measurements reported by Pelfrey and Liburdy.

Validation included:

- Velocity profile at X = 6
- Temperature profiles at X = 3.35
- Temperature profiles at X = 6.69
- Temperature profiles at X = 15.75
- Temperature profiles at X = 38.2

Good agreement was obtained between the numerical predictions and the experimental data for both the velocity and thermal fields.
---

## Post-processing

Results were analysed using

- ParaView
- SciDavis
