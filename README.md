# Discrete-Event Trophic Ecosystem Simulation

An object-oriented, stochastic agent-based simulation modeling multi-species trophic interactions on a toroidal grid, developed during the Programming Fundamentals coursework at Instituto Superior Técnico (IST).

---

## Overview
This project simulates the temporal and spatial evolution of an ecological system governed by stochastic discrete events. Organisms are distributed across a $(2N + 1) \times (2N + 1)$ periodic toroidal lattice and interact through trophic relationships (water, producers, primary consumers, and apex predators).

---

## Key Features
- **Object-Oriented Architecture:** Modular design featuring decoupled entities (`Celula`, `Grelha`, `Evento`, `CEP`).
- **Discrete-Event Simulation (DES):** Custom event scheduling priority queue (`CEP`) managing chronological event execution (`loc`, `chv`, `sec`, `epid`).
- **Stochastic Processes:** Event inter-arrival times modeled via inverse transform sampling of exponential distributions ($T = -m \ln U$).
- **Spatial Grid Mechanics:** Toroidal periodic boundary wrapping with localized Moore-neighborhood scanning algorithms.
- **Ecological Dynamics:** Survival logic evaluating predator-to-prey ratios, metabolic resilience thresholds, and environmental shocks (droughts, rainfall, epidemics).

---

## Tech Stack
- **Language:** Python 3.x
- **Libraries:** NumPy, Matplotlib, Random
- **Paradigm:** Object-Oriented Programming (OOP) & Discrete-Event Simulation (DES)

---

## Academic Context
- **Institution:** Instituto Superior Técnico (IST), Universidade de Lisboa
- **Degree:** BSc in Industrial Engineering and Management
- **Course:** Programming Fundamentals
