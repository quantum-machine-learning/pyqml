# PyQML

## Quantum Combinatorial Optimization Problem Solver (QCOPS)

QCOPS aims to provide an easy-to-use API for solving intermediate-scale optimization problems in practice.

The Quantum Approximate Optimization Algorithm (QAOA) is one of the most promising algorithms to achieve quantum advantages on current noisy intermediate scale quantum (NISQ) devices. It is very well suited to solving combinatorial optimization problems.

Well-known quantum SDKs such as Qiskit and Pennylane provide convenient interfaces for using the QAOA. However, these lack essential features to efficiently move a sufficiently hard problem from an experimental phase to production maturity.

The missing features are:

1. caching - storing intermediate results and continuing optimization processes.
2. error mitigation - integration of methods for error mitigation
3. qubit reduction - minimizing the number of qubits needed to solve a problem
4. customizability - a modular implementation that allows replacing everything.

QCOPS provides these features.

