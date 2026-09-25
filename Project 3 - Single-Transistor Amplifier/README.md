# Project 3 - Single-Transistor Amplifier

## Overview

This project explores the design, simulation, and physical implementation of a single-transistor amplifier. The objective is to deliver an input signal of up to ±0.5 V from a source with 100 Ω internal resistance to a 100 Ω load with good linearity and less than 10% attenuation.

## Design Requirements

- Use a single MOSFET or BJT without op-amps.
- Operate using the DC supplies available from the Digilent module.
- Test using the Digilent function generator with a 100 Ω series resistor.
- Demonstrate multiple waveforms and input amplitudes up to 0.5 V peak.

## Performance Evaluation

The project compares calculated, simulated, and measured gain, with particular attention to midband performance and linearity at the maximum input amplitude. The target overall voltage-gain magnitude is greater than 0.9, measured from the source signal before the 100 Ω series resistor to the loaded output.

## Video Report

[Watch the video report on YouTube](https://www.youtube.com/watch?v=XB7dzbdB1lw)

The video report presents the transistor and topology choices, component calculations, simulation setup and results, physical circuit connections, and measured waveforms. It also compares expected and measured performance and demonstrates linearity at a 0.5 V input amplitude.
