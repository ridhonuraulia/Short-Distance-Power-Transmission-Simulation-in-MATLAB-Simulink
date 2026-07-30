# Short-Distance Power Transmission Simulation in MATLAB Simulink

This repository contains a MATLAB Simulink-based simulation of a short-distance power transmission system.  
The main purpose of this project is to demonstrate how short-distance transmission can be modeled and analyzed using Simulink in MATLAB.

## Project Goals

- Simulate a short-distance power transmission system
- Observe how electrical power is transmitted over a short line
- Analyze the phasor behavior and output voltage in the system
- Provide a simple educational model for understanding basic transmission concepts

## Software Requirements

- MATLAB R2024b
- Simulink

## How to Run

1. Download or clone this repository.
2. Open the project in MATLAB R2024b.
3. Run the Simulink model directly.
4. Observe the simulation results, including:
   - phasor values
   - output voltage
   - transmission behavior

## Main Results

The main results of this simulation allow us to observe:
- the phasor relationships in the system
- the voltage generated at the output
- the effect of short-distance transmission on the system

## Disclaimer

The transmission topology used in this project was provided by my lecturer.  
I did not design the topology itself.  
My role in this repository is to analyze and simulate the system behavior.

## Notes

This project can be extended to represent longer-distance transmission by adding an extra transformer at the junction point.  
For example:
- one step-up transformer
- one step-down transformer

This makes it possible to simulate a higher-voltage transmission path before stepping the voltage back down.

## Repository Structure

- `src/` — Simulink model files and related scripts
- `notebooks/` — analysis notes and simulation observations
- `docs/` — supporting documentation and references
- `figures/` — simulation screenshots and output plots

## Author

Created for learning and simulation purposes.
