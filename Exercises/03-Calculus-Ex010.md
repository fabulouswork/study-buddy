---
topic: Calculus
subtopic: integration
technique: u-substitution
generated: 2026-06-13
status: correct
attempts: 1
---

# Exercise: Chat Session Substitution (Ex010)

## Problem 1

\[
\int \frac{2x}{x^2 + 1} \, dx
\]

## Solution

Let u = x² + 1, du = 2x dx

∫ 2x/(x²+1) dx = ∫ du/u = ln|u| + C = ln|x²+1| + C

Since x²+1 > 0 always: **ln(x²+1) + C**

## Problem 2

\[
\int x\sqrt{x+1} \, dx
\]

## Solution

Let u = x + 1, then x = u - 1, dx = du

∫ x√(x+1) dx = ∫ (u-1)u^(1/2) du = ∫ (u^(3/2) - u^(1/2)) du

= (2/5)u^(5/2) - (2/3)u^(3/2) + C

= **(2/5)(x+1)^(5/2) - (2/3)(x+1)^(3/2) + C**
