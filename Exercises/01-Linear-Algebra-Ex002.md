---
topic: Linear Algebra
generated: 2026-06-02
status: correct
attempts: 1
---

# Exercise: Vector Spaces and Closure

## Problem

You're designing a quantum system and need to check whether certain sets of states form valid vector spaces. Remember: a set is a vector space if it's closed under addition and scaling, and contains the zero element.

### Part A: Polynomials of Degree ≤ 2

Consider the set $V = \{a + bx + cx^2 \mid a, b, c \in \mathbb{R}\}$ — all polynomials of degree at most 2.

1. If $p(x) = 1 + 2x + x^2$ and $q(x) = 3 + x^2$, what is $p(x) + q(x)$? Is it in $V$?
2. What is $2p(x)$? Is it in $V$?
3. What is the zero element of this set?
4. Is $V$ a vector space? Why or why not?

### Part B: Quantum Superposition

In a two-level quantum system, suppose the valid basis states are:
$$
|0\rangle = \begin{pmatrix} 1 \\ 0 \end{pmatrix}, \quad |1\rangle = \begin{pmatrix} 0 \\ 1 \end{pmatrix}.
$$

You claim that any superposition like $|\psi\rangle = \frac{1}{\sqrt{2}}|0\rangle + \frac{1}{\sqrt{2}}|1\rangle$ is a valid state.

Why can you add these basis states together and still have a valid state? (Hint: think about vector space closure.)

### Part C: Non-Example — Rotated Polynomials

Consider $W = \{a + bx \mid a, b \in \mathbb{R}, a + b = 1\}$ — polynomials where the sum of the first two coefficients equals 1.

1. Is the zero polynomial $0$ in $W$?
2. If $p(x) = 1 + 0 \cdot x$ and $q(x) = 0.5 + 0.5x$ (both in $W$), is $p(x) + q(x)$ in $W$?
3. Is $W$ a vector space? Why or why not?

---

## Your Turn

Work through all three parts. For each, show your reasoning clearly. When ready, share your answers.
