# Active-Passive-Dendritic-Backpropagation
NEURON simulations of active and passive action-potential backpropagation in dendrites using cable theory.

# Active and Passive Dendritic Backpropagation

This project investigates the propagation of somatic action potentials along a dendrite using the NEURON simulation environment and cable theory.

## Project Overview

A somatic compartment containing Hodgkin-Huxley channels was connected to a 1000 µm dendrite. Two dendritic models were investigated:

- **Passive dendrite:** the dendrite contains passive leak properties.
- **Active dendrite:** the dendrite contains Hodgkin-Huxley voltage-gated channels.

The two models are compared to understand how active ion channels influence action-potential propagation along dendrites.

## Simulations

The project investigates:

- Action-potential propagation along the dendrite
- Peak action-potential amplitude at different distances from the soma
- Propagation latency with distance
- Effects of axial resistance (`Ra`)
- Effects of membrane resistance (`Rm`)
- Effects of membrane capacitance (`Cm`)
- Comparison of passive and active backpropagation

## Model

The model consists of:

- A somatic compartment with Hodgkin-Huxley channels
- A 1000 µm dendrite
- Dendritic diameter of 2 µm
- Compartmentalization based on the space constant at 100 Hz
- Brief somatic current injection to initiate a single action potential

For the passive model, the dendrite contains passive leak properties.

For the active model, Hodgkin-Huxley channels are inserted into the dendrite with specified sodium and potassium conductances.

## Measurements

Using the `minmax` mechanism, the model measures:

- Distance from the soma
- Peak membrane potential
- Time at which the peak occurs

These measurements are used to examine **signal attenuation and propagation delay** along the dendrite.

## Cable Theory

The simulations explore how neuronal cable properties influence electrical signal propagation.

Important parameters include:

- **Ra** – axial resistance
- **Rm** – membrane resistance
- **Cm** – membrane capacitance

Changing these parameters allows their effects on dendritic signal propagation to be investigated.

## Tools

- NEURON Simulation Environment
- HOC
- Hodgkin-Huxley model
- Cable theory
- `minmax.mod`

## Learning Objectives

This project was developed to understand:

1. Passive electrical signal propagation in dendrites
2. Active backpropagation of action potentials
3. The effects of `Ra`, `Rm`, and `Cm` on signal propagation
4. Action-potential attenuation with distance
5. Propagation delay along dendrites
6. The role of voltage-gated ion channels in active signal propagation
