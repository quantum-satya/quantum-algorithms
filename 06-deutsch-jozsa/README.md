# Deutsch–Jozsa Algorithm

This notebook demonstrates the **Deutsch–Jozsa Algorithm** using Qiskit 2.x and **Statevector simulation**.

## 🧠 Overview

The Deutsch–Jozsa problem is a generalization of the Deutsch Algorithm:

- Function `f(x)` takes **n qubits** and outputs **1 bit**.
- Guaranteed to be either:
  - **Constant:** all outputs are 0 or all are 1
  - **Balanced:** half outputs 0, half outputs 1
- **Goal:** Determine the type of function with a **single evaluation** using a quantum computer.

## ⚡ Notebook Features

- Builds **constant** and **balanced** oracles
- Implements Deutsch–Jozsa circuit
- Uses **Statevector** for simulation
- Visualizes:
  - Circuit diagrams
  - Probabilities histogram
  - Bloch sphere (for 1-qubit example)
- Fully compatible with **Qiskit 2.x**

## 📺 YouTube Video

Watch the video explaining this notebook in detail:  
[Deutsch–Jozsa Algorithm | Quantum-Satya](https://youtube.com/@quantumsatya)

## 📂 How to Run

1. Clone the repo
2. Activate your Qiskit virtual environment:
   ```bash
   source ~/QuantumSatya/qiskit-env/bin/activate
