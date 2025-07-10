# Fidelity-Comparison
Comparison of quantum state fidelity between Trotterized evolution and exact unitary evolution, using Python and NumPy/SciPy.

# Fidelity Comparison: Trotter vs Exact Evolution

This repository explores quantum state fidelity between Trotterized time evolution and exact unitary evolution. The simulation is based on a simple spin chain model (e.g., transverse-field Ising model), implemented in Python using NumPy and SciPy.

## Motivation

Trotter-Suzuki decomposition is widely used to simulate time evolution in quantum systems with non-commuting Hamiltonians. But how accurate is it compared to exact evolution?  
This project quantifies the fidelity loss from Trotterization, as a function of time and number of Trotter steps.

## Features

- Simulates time evolution under both:
  - Exact Hamiltonian exponentiation
  - Trotterized approximations (1st & 2nd order)
- Computes **quantum state fidelity** over time
- Supports multi-qubit spin chain (e.g., 3–6 qubits)
- Visualizes fidelity decay and convergence behavior
