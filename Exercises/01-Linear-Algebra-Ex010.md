# Exercise 010 — Tensor Products

## Topic
Linear Algebra — Tensor Products

## Difficulty
Medium

## Questions

### 1. Kronecker product
Let **I** be the 2×2 identity matrix [[1, 0], [0, 1]] and **H** be the Hadamard matrix (1/√2)[[1, 1], [1, -1]].

Compute **I ⊗ H** (a 4×4 matrix).

### 2. Separability check
Determine whether the following 4-component vector can be written as **u ⊗ v** for some **u, v ∈ ℝ²**:

|ψ⟩ = (0, 2, 3, 0)

If it *can* be written as a tensor product, find **u** and **v**.

### 3. Quantum meaning
The Bell state |Φ⁺⟩ = (1/√2)(|00⟩ + |11⟩) uses the shorthand where |00⟩ = **e₁** ⊗ **e₁**, |01⟩ = **e₁** ⊗ **e₂**, etc.

Write |Φ⁺⟩ explicitly as a 4-component vector. Then verify whether it is entangled (impossible to factor) or separable.

### 4. Stretch — Bloch sphere
A general qubit state is |ψ⟩ = cos(θ/2)|0⟩ + e^(iφ) sin(θ/2)|1⟩, where |0⟩ = (1,0) and |1⟩ = (0,1).

What is the tensor product |ψ⟩ ⊗ |ψ⟩ in component form? For what values of θ, φ (if any) is this the same as the Bell state |Φ⁺⟩?

---

*Quantum relevance: The Kronecker product I ⊗ H is the first step in building the circuit that creates Bell states — apply H to the first qubit, then CNOT to entangle them.*
