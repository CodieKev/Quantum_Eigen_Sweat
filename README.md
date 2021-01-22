# Quantum_Eigen_Sweat
The traditional way of finding minimum eigenvalue of a hermitian matrix consists of Semi-Classical method where we use Classical Optimization and variational principles to find the lowest eigenvalue of a matrix. 

Here we try to find a new method  to find the lowest eigenvalue without optimization. We start with only 2x2 Hermitian Matrix as our target matrix. We use two methods- "Quantum Approach" and "Semi-Quantum Approach" method.

The "Quantum Approach" method, is implemented using Quantastica's Circuit Generator. If we input an initial statevector and the final statevector to the generator, it creates a circuit that takes initial state to the final state. We prepare a set of initial states that encode various matrices and we prepare a corresponding set of final states corresponding to lowest energy eigenstates of each encoded matrix.We assume that, for a sufficient set of trial initial states and final states, the circuit generator is able to generate a circuit that can find lowest energy eigenvector for any hermitian matrix of dimension 2x2.

The second method i.e the "Semi-Quantum" method, we try to find some correlation between the Eigenstate and its matrix. Getting the correlation, fitting it with curves to make some prediction to check our method.
