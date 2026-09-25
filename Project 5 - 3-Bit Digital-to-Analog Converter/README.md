# Project 5 - 3-Bit Digital-to-Analog Converter

## Overview

Design, simulation, and hardware testing of a 3-bit digital-to-analog converter (DAC) using a binary-weighted resistor network and an inverting op-amp summing stage. Three digital inputs represent eight binary codes, producing a corresponding analog staircase output.

## Circuit Design

- Uses 10 kΩ, 20 kΩ, and 40 kΩ resistors to weight the three input bits.
- Includes op-amp input buffers to minimize loading on the digital lines, targeting less than 1 µA per input.
- Uses an inverting summing amplifier to convert the weighted currents into a negative output voltage.
- Explores a 5 V full-scale design target and the practical effects of logic levels, feedback resistance, and output saturation.

## Simulation and Testing

LTspice is used to simulate circuit behavior. Hardware testing uses the Analog Discovery 3 and Digilent WaveForms to generate binary input sequences and measure the analog output.

The report examines transfer characteristics, gain error, differential non-linearity (DNL), and offset error. It also discusses resistor tolerances, op-amp limitations, and the R–2R ladder as an alternative architecture.

## Hardware Observations

The report describes a hardware configuration using 3.3 V digital inputs and a 10 kΩ feedback resistor, with output clipping near the negative supply rail at the highest codes. These limitations distinguish the prototype from the original 5 V logic design target.

## Project Report

The uploaded report includes circuit schematics, design calculations, simulation results, hardware photographs, measured waveforms, and error analysis.
