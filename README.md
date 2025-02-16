# CS682_Quantum_Computing IITK

The assignments involve designing custom quantum circuits using basic quantum gates in Qiskit.

## Assignment 1

- Develop a swap circuit using custom inputs (without using the built-in swap function) and verify its action on the state `|0⟩|+⟩` via a state-vector simulator.
- Create and simulate the entangled state `(|01⟩ + |10⟩)/√2`; apply a CNOT with the second qubit as control, evaluate entanglement post-operation, and visualize the results over 100 runs.
- Design a circuit for the operation `x, y, z → x, y, z⊕(x⊕y)'` without direct x–z interaction and demonstrate its action as a matrix.

## Assignment 2

- Implement the Deutsch-Jozsa algorithm for a custom function `f: {0,1}³ → {0, 1}` defined by `f(x, y, z) = x ⊕ y ⊕ z'` to determine whether the function is balanced or constant.
- Construct an efficient quantum circuit for a half-adder and extend it to perform a custom ternary operation `(x, y, z) → (x, t, x⊕y⊕z)` where `t = ((x⊕y) ∧ z) ∨ (x ∧ y)`.
