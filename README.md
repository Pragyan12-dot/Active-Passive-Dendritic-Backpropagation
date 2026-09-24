# Active-Passive-Dendritic-Backpropagation
NEURON simulations of active and passive action-potential backpropagation in dendrites using cable theory.

# Active and Passive Dendritic Backpropagation

This project explores the propagation of action potentials from the soma into a dendrite using the **NEURON simulation environment** and **cable theory**.

## Project Overview

A somatic compartment containing Hodgkin-Huxley ion channels was connected to a long dendritic compartment. The dendrite was initially modeled using passive electrical properties and later with Hodgkin-Huxley channels to compare passive and active backpropagation.

The simulations investigate how neuronal parameters affect the propagation of action potentials along the dendrite.

## Simulations

The project includes:

- Passive backpropagation of a somatic action potential along a dendrite
- Analysis of action-potential amplitude with distance from the soma
- Analysis of propagation latency with distance from the soma
- Effect of axial resistance (`Ra`) on propagation
- Effect of membrane resistance (`Rm`) and membrane capacitance (`Cm`)
- Active backpropagation after inserting Hodgkin-Huxley channels into the dendrite
- Comparison between passive and active propagation

## Theory

The simulations are based on **cable theory**, which describes how electrical signals propagate through neuronal processes.

Important parameters investigated include:

- **Axial resistance (`Ra`)** – affects current flow along the dendrite
- **Membrane resistance (`Rm`)** – affects current leakage across the membrane
- **Membrane capacitance (`Cm`)** – affects membrane charging and temporal response

## Tools

- **NEURON Simulation Environment**
- **HOC**
- Cable theory
- Hodgkin-Huxley model

## Outputs

The simulations generate plots showing:

- Action-potential amplitude vs. distance from the soma
- Action-potential latency vs. distance from the soma
- Changes in propagation with different biophysical parameters
- Comparison of passive and active backpropagation

## Learning Objectives

This project was carried out to understand:

1. Passive electrical signal propagation in dendrites
2. The relationship between cable properties and signal attenuation
3. The effects of neuronal biophysical parameters on propagation
4. Active regeneration of action potentials in dendrites

**Pragyan Bagchi**
