# Switching Characteristics and Data Sheet Realization of MOSFET

This project investigates the switching characteristics of MOSFETs, focusing on practical performance metrics and data sheet realization. The work includes simulation, hardware experiments, and design of gate driver circuits to analyze MOSFET switching behavior in power electronic applications.

## Project Authors
- Donda Yashashwini (Roll No: 220002032)
- Vadithya Dhanalaxmi (Roll No: 220002079)

Guided by Dr. B. Prathap Reddy, Department of Electrical Engineering, Indian Institute of Technology Indore, September 2025.

## Overview

### Introduction
MOSFETs (Metal Oxide Semiconductor Field Effect Transistors) are essential components in modern electronics used for switching and power control. Their operation depends on the gate voltage, allowing them to work in cutoff, linear, or saturation modes. Key switching parameters include turn-on delay, rise time, turn-off delay, and fall time, which influence efficiency and energy losses.

### Motivation
Understanding and improving MOSFET switching performance is crucial for developing efficient power electronic circuits, reducing energy losses, and enhancing device reliability.

## Project Components

### Literature Review
- Study of gate driver circuits: isolated and non-isolated types.
- Use of double pulse test methods to assess switching losses and device timing characteristics.
- Analysis of bridge configurations with surge suppression techniques for stable MOSFET operation.

### Switching Realization
- Design and simulation of non-isolated gate driver circuits with varying gate resistances affecting switching speed and gate currents.
- Application of double pulse tests to measure MOSFET switching times and losses.
- Simulation of single-switch buck converters analyzing the impact of gate resistance on switching losses, conduction losses, and overall efficiency.

### Hardware Setup and Experimental Results
- Implementation of double pulse test using TMS320F28379D LaunchPad to generate precise gate pulses.
- Verification of simulation results with hardware double pulse waveforms.
- Design of isolated gate driver PCBs to ensure robust MOSFET operation with galvanic isolation and EMI reduction.

## Key Findings
- Low gate resistance leads to faster switching but higher peak gate currents.
- Switching losses increase with gate resistance due to longer switching intervals.
- Proper design of gate drivers and surge suppression methods is critical to avoid device damage and enhance performance.

## Future Work
- Further simulations and hardware validation of half-bridge buck converter configurations.
- Comparison of measured switching characteristics with manufacturer datasheet specifications.
- Development of isolated gate driver circuit prototypes.

## References
- Key textbooks and application notes on MOSFET operation and gate drivers.
- Manufacturer datasheets and technical documentation.

## Usage
This repository provides simulations, hardware design files, and detailed analysis useful for power electronics researchers and engineers working with MOSFET switching circuits. Users can replicate the tests, modify gate driver designs, and validate MOSFET performance for their applications.

---

Feel free to explore the files and simulations to understand practical MOSFET switching characteristics and how they impact power electronic circuit design.
