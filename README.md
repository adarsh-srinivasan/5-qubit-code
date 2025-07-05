# 5-qubit-code

This notebook implements the 5-qubit error correctiung code in qiskit (https://en.wikipedia.org/wiki/Five-qubit_error_correcting_code)
We implement a circuit that initialized the logical zero state, runs it through a pauli error channel with probability p, and outputs the probability that ther error is correctible. To obtain the above-mentioned circuit, use the function correction_circuit(p). To check our results, run the final code-cell with different values of p. 
