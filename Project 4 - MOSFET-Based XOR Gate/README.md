# Project 4 - MOSFET-Based XOR Gate

## Overview

Design, construction, and hardware testing of a 12-transistor CMOS XOR gate using complementary MOSFET arrays. The circuit implements **Y = A ⊕ B**, producing a HIGH output when its two inputs differ.

| A | B | Y |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

## Design and Testing

- Discusses ideal PMOS/NMOS sizing and the limitations of fixed transistor dimensions in hardware.
- Verifies all four input combinations using the Analog Discovery 2 pattern generator and logic analyzer.
- Measures output HIGH and LOW voltages with one input held at +5 V, then repeats with the inputs exchanged.
- Evaluates rise time, fall time, and propagation delays with a 100 nF output load.

## Reported Timing Results

| Metric | Measured value |
|---|---|
| Rise time | 374.15 µs |
| Fall time | 262.73 µs |
| LOW-to-HIGH propagation delay | 300 µs |
| HIGH-to-LOW propagation delay | 83.3 µs |
| Average propagation delay | 191.65 µs |

These results apply to the tested circuit with the 100 nF output load.

## Project Report

The uploaded report includes the circuit schematic, hardware photographs, transistor-sizing discussion, functional verification, static voltage measurements, and timing calculations. Evaluation is based on physical measurements; simulations were not required for this project.
