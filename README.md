# ERC Recoverability Model

Minimal, falsifiable models of recoverability boundaries in dynamical systems.

---

## Overview

This repository contains a set of minimal dynamical models exploring whether system failure can emerge from loss of **recoverability**, rather than loss of state space.

The central hypothesis is that:

> System function may depend on whether recovery processes can keep up with temporal demand within finite time windows.

---

## Structure

The framework is organized into three modules:

### ERC-D — Deterministic Boundary
- Minimal dynamical system
- Demonstrates loss of recoverability without loss of state space
- Identifies a critical boundary under increasing constraint

📁 `ERC-D/`

---

### ERC-S — Stochastic Extension
- Introduces noise and variability
- Tests robustness of the boundary
- Evaluates return probability under perturbations

📁 `ERC-S/`

---

### ERC-R — Redox Interpretation
- Interprets recoverability in biological systems
- Focus on oxygen-mediated redox dynamics
- Connects recovery to kinetic constraints and buffering capacity

📁 `ERC-R/`

---

## Key Idea

Across all models:

- The system can still *reach* a state  
- But may lose the ability to *return* to it  

This suggests a transition from:

→ accessible dynamics  
to  
→ dynamically inaccessible regimes  

---

## Reproducibility

Each module contains:

- A paper (PDF)
- A runnable notebook
- Supporting figures

All models are intentionally minimal and designed to be falsifiable.

---

## License

- Code: MIT License  
- Papers: CC BY 4.0  

---

## Author

Jaime Ojeda  
with assistance from AI-based modeling tools
