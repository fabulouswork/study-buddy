---
topic: Linear Algebra
generated: 2026-06-04
status: correct
attempts: 1
---

# Exercise 9: Inner Products & Projections

## Problem

You have three vectors in $\mathbb{R}^3$:
$$u = (1, 2, 0)$$
$$v = (1, 0, 0)$$
$$w = (0, 1, 0)$$

### Part A: Projections
Compute the projection of $u$ onto $v$. Call it $\text{proj}_v(u)$.

Then compute the component of $u$ orthogonal to $v$. Call it $r$.

Verify that $r \cdot v = 0$ (orthogonality check).

### Part B: Orthonormal Basis

Notice that $v$ and $w$ are orthogonal and both have length 1 — they form an orthonormal basis for the $xy$-plane.

Express $u$ in the form:
$$u = a \, v + b \, w + c \, n$$

where $n$ is the unit vector in the $z$-direction (which is orthogonal to both $v$ and $w$).

Find $a$, $b$, and $c$ using inner products.

### Part C: Parseval's Identity

Verify Parseval's identity:
$$|u|^2 = a^2 + b^2 + c^2$$

Compute both sides and check they match.

---

## Hints (if you get stuck)

**Hint 1:** For projections, use the formula $\text{proj}_v(u) = \frac{u \cdot v}{v \cdot v} v$.

**Hint 2:** For Part B, remember that if $v, w, n$ form an orthonormal basis, then $a = u \cdot v$, $b = u \cdot w$, $c = u \cdot n$.

**Hint 3:** What is $|u|^2$ by direct computation? $(1)^2 + (2)^2 + (0)^2 = ?$
