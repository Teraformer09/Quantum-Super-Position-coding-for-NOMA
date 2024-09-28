Quantum Superposition Circuit

This project demonstrates a quantum circuit that applies amplitude amplification and noise mitigation techniques using dynamical decoupling for 10 users simultaneously. The goal is to amplify specific target states in superposition and manage noise by incorporating decoupling methods. The system is designed to simulate interactions between qubits using CNOT gates instead of Controlled-Phase (CP) gates, which reduces error while maintaining functionality.

Table of Contents:-
Overview
Project Structure
Features
Usage
Dependencies
Installation
Running the Code

#Overview
In this project, a quantum circuit simulates 10 users interacting simultaneously at a single time instance using quantum superposition. The circuit performs:
Amplitude amplification: Using Grover's algorithm-like operations to amplify target states
Noise mitigation: Dynamical decoupling is applied to mitigate errors and noise in the circuit.
Optimized gate structure: Controlled-NOT (CNOT) gates are used instead of Controlled-Phase (CP) gates, which reduces the error rate in the system.

The project outputs the final measurement results for all 10 users in the quantum system at a specific time instance.

#Project Structure
.
├── QuantumSuperpositionCircuit.ipynb   # Jupyter Notebook for the circuit
├── quantum_superposition_circuit.py    # Python file containing the main code
├── README.md                           # Project documentation
└── LICENSE                             # Project license

#Features

1. Amplitude Amplification: Amplifies the probability of finding the system in a desired target state for each user.
2. Dynamical Decoupling: A noise mitigation technique applied to reduce quantum decoherence by using sequences of X gates.
3. Efficient Gates: Replaces Controlled-Phase (CP) gates with Controlled-NOT (CNOT) gates to reduce error rates.
4. Multiple Users: Simulates a system for 10 users, each represented by a unique target state.
5. Single Time Instance Output: Outputs the quantum measurement results for a specific time instance (t0 - t1)

#Usage
This quantum circuit project can be used to explore:
Quantum superposition states and how to amplify them.
Noise mitigation techniques like dynamical decoupling.
The impact of gate optimizations in quantum circuits.

#Dependencies
The project uses the following libraries:
Qiskit
NumPy
Matplotlib (for plotting the histogram of results)

#Installation

1. Clone the repository:
git clone https://github.com/yourusername/QuantumSuperpositionCircuit.git
cd QuantumSuperpositionCircuit

2. Install the required dependencies:
pip install -r requirements.txt

3. Open the Jupyter notebook QuantumSuperpositionCircuit.ipynb to explore the code, or directly run quantum_superposition_circuit.py using Python.

#Running the Code
To run the Python code:
1. Make sure you have a Qiskit Aer simulator installed.
2. Execute the following command to run the script:
python quantum_superposition_circuit.py

The script will print the output counts of the quantum circuit and plot a histogram showing the results of the quantum measurement for the 10 users.
