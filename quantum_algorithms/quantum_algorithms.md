# Quantum Algorithms

## Deutsch Jozsa algorithm

- Significance: First algorithm to demonstrate quantumness
- Problem: Determine a hidden function is constant or balanced
- Algorithm: 
- Implementation
![](images/dj_algorithm_circuit.png)
### Exercises

1. Implement a DJ N=3 Constant circuit
2. Implement a DJ N=3 Balanced circuit

## Grover’s algorithm

- Significance: Quadratic speed up
- Problem: Unstructured search problem
![](images/grover_unstructured_search.png)
- Algorithm: 
![](images/grover_step1.jpg)
![](images/grover_step2.jpg)
![](images/grover_step3.jpg)
- Implementation:
![](images/grover_circuit_high_level.png)
![](images/grover_n=2_a=00.png)
### Exercises
 
1. Implement Grover N=2, A=01
2. Implement Grover N=3, A=010, 1 iteration
3. Implement Grover N=3, A=011, 2 iterations

## Shor’s algorithm

- Significance: Exponential speed up
- Problem: Factorization

Period finding
Modular arithmetic


- Algorithm: 

Quantum fourier transform
Quantum phase estimation


Classical part
Quantum part: period finding subroutine

- Implementation:
![](images/shor_circuit.svg)
### Exercises

