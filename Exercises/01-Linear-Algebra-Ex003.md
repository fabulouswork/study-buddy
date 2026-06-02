---
topic: Linear Algebra
generated: 2026-06-02
status: correct
attempts: 1
---

# Exercise: Linear Transformations and Matrices

## Problem

You're working with a quantum system and need to verify and apply linear transformations.

### Part A: Is it Linear?

For each map below, determine whether it is a linear transformation $T: \mathbb{R}^2 \to \mathbb{R}^2$. If not, explain which condition fails (additivity or homogeneity).

1. $T\begin{pmatrix} x \\ y \end{pmatrix} = \begin{pmatrix} 3x \\ -y \end{pmatrix}$

2. $T\begin{pmatrix} x \\ y \end{pmatrix} = \begin{pmatrix} x^2 \\ y \end{pmatrix}$

3. $T\begin{pmatrix} x \\ y \end{pmatrix} = \begin{pmatrix} x + y \\ 2x \end{pmatrix}$

### Part B: Matrix Representation

For the linear transformation $T\begin{pmatrix} x \\ y \end{pmatrix} = \begin{pmatrix} -y \\ x \end{pmatrix}$:

1. What is the geometric effect of $T$? (Hint: test it on $\begin{pmatrix}1\\0\end{pmatrix}$ and $\begin{pmatrix}0\\1\end{pmatrix}$.)
2. Write down the $2 \times 2$ matrix $M$ that represents this transformation.
3. Verify your matrix by computing $M\begin{pmatrix} 1 \\ 1 \end{pmatrix}$ and checking it equals $T\begin{pmatrix} 1 \\ 1 \end{pmatrix}$.

### Part C: Scaling

The scaling transformation $S_c: \mathbb{R}^2 \to \mathbb{R}^2$ scales all vectors by a factor $c$ (where $c > 0$).

1. Write down the matrix for $S_2$ (scaling by factor 2).
2. Is $S_c$ a linear transformation for any $c$? Why?
3. In quantum mechanics, scaling a state by a global factor doesn't change the physics. What does this suggest about our choice of basis?
