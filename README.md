# 5-qubit-code

This notebook implements the 5-qubit error correcting code in qiskit (https://en.wikipedia.org/wiki/Five-qubit_error_correcting_code)
We implement a circuit that initializes the logical zero state, runs it through a pauli error channel with probability p, and outputs the probability that ther error is correctible. To obtain the above-mentioned circuit, use the function correction_circuit(p). To test, use the function test(p), to get the probability that the circuit measures a component of the logical 0 state. To check our results, run the final code-cell with different values of p. 
