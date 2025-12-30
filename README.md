# Calcium-Based Synaptic Plasticity Models in NEST/NestML

## Overview

This repository contains two computational models developed using **NestML**:

* a **neuron model**, and
* a **synapse model**

Both models incorporate the equations and mechanisms described in **Chindemi et al.** to simulate a **calcium-based synaptic plasticity mechanism**.

The models are designed to be used within the **NEST simulator**, and example simulations are provided through a **Jupyter Notebook** interface.

## Models

### Neuron Model

* Implemented in **NestML**
* Designed to interact with calcium-dependent synaptic dynamics
* Compatible with NEST simulations

### Synapse Model

* Implemented in **NestML**
* Incorporates calcium-based plasticity rules derived from **Chindemi et al.**
* Tracks calcium dynamics to drive synaptic weight changes

## Simulation Environment

* **Simulator:** NEST
* **Modeling Language:** NestML
* **Interface:** Jupyter Notebook

The Jupyter Notebook included in this repository demonstrates how to:

* compile and load the NestML models,
* set up the neuron–synapse network in NEST,
* run simulations, and
* observe calcium-driven synaptic plasticity effects.

## Reference

The synaptic plasticity mechanism implemented here is based on the work of:

> Chindemi et al., *[full citation to be added]*

Please refer to the original publication for theoretical background and detailed derivations of the calcium-based plasticity equations.

## Repository Structure

```text
.
├── Version/                      # Old versions of the code
├── "name".nestml/                # Neuron and Synapse models
├── Jypiter_FinalTest.ipynb       # Jupyter Notebook(s) for simulation and analysis
├── README.md                     # Project documentation
```

## Requirements

* NEST Simulator
* NestML
* Python (with Jupyter Notebook support)

## Usage

1. Install NEST and NestML.
2. Compile the NestML models.
3. Open the provided Jupyter Notebook.
4. Run the simulation cells to reproduce calcium-based synaptic plasticity behavior.

## License

---

## Acknowledgments

* NEST Simulator and NestML development teams
* Chindemi et al. for the original calcium-based plasticity framework
