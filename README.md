# Quantum Computing Basics

Implementation of quantum circuits using Qiskit, demonstrating fundamental quantum computing concepts.

## Implementations

1. **Basic Circuit Operations**
   - Single qubit operations (H, X gates)
   - Measurement and visualization
   - Using Qiskit's SamplerV2 for simulation

2. **Bell State Creation**
   - Two-qubit entanglement
   - Using H and CNOT gates
   - Probabilistic error introduction (20%)

3. **State Preparation and Measurement**
   - Preparing |+⟩ and |1⟩ states
   - Entanglement with CX gate
   - Measurement statistics analysis

4. **Quantum Coin Flip Game**
   - Alice prepares |+⟩ state
   - Bob's random basis measurement (X/Z)
   - Win condition: Bob wins on measuring |+⟩ or |0⟩
   - Advanced version with quantum-controlled measurement

## Requirements
- Python 3.x
- Qiskit
- Qiskit-Aer
- Matplotlib

## Installation
```bash
pip install qiskit qiskit-aer matplotlib
```



## Usage
Run the Jupyter notebooks to explore quantum computing concepts from basic operations to the quantum coin flip game.
