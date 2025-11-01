# 🧩 Quantum Algorithms with Qiskit

**Author:** [Satya Pal](https://github.com/quantum-satya)  
**Environment:** Python · Qiskit · Jupyter  
**License:** MIT  

---

## 🎯 Overview
This repository implements foundational **quantum algorithms** using IBM’s open-source framework **Qiskit**.  
Each algorithm is built from scratch with circuit illustrations, code explanations, and simulation results.

> 🧪 Purpose: To build a practical foundation in quantum software and contribute to the Qiskit ecosystem.

---

## 🧬 Algorithms Implemented

| # | Algorithm | Description | Folder |
|---|------------|--------------|---------|
| 1 | **Deutsch Algorithm** | Distinguishes between constant and balanced functions using a single oracle query. | [`deutsch/`](./deutsch) |
| 2 | **Deutsch–Jozsa Algorithm** | Generalization of Deutsch for n-bit functions (coming soon). | [`deutsch-jozsa/`](./deutsch-jozsa) |
| 3 | **Grover’s Algorithm** | Quantum search algorithm achieving quadratic speed-up. | [`grover/`](./grover) |
| 4 | **Simon’s Algorithm** | Foundation of quantum advantage through hidden period finding. | [`simon/`](./simon) |

---

## ⚙️ Requirements

Create and activate your environment:
cd ~/QuantumSatya
python3 -m venv qiskit-env
source qiskit-env/bin/activate
pip install qiskit jupyter matplotlib

## 🚀 Running a Notebook
cd ~/QuantumSatya/quantum-algorithms
source ~/QuantumSatya/qiskit-env/bin/activate
jupyter notebook
Each folder (e.g., deutsch/) contains a Jupyter notebook demonstrating one algorithm step-by-step.

## 🌟 Author’s Note
“Quantum algorithms represent a new way of thinking about computation —
I’m documenting this journey from the ground up to share what I learn and to contribute
to India’s growing quantum ecosystem.”

— Satya Pal, aspiring Quantum Software Engineer

## 📜 License
This project is licensed under the MIT License.

