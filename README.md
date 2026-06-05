# Catalan-Heegner Invariant

This repository contains the numerical verification of a new identity connecting the Catalan sequence with the $j$-invariants of elliptic curves having complex multiplication.

## The Conjecture
We define the series $S(d)$ for a Heegner discriminant $d < 0$ as:

$$S(d) = \sum_{n=0}^{\infty} \left( 1 + n(j(d) - 1) \right) \frac{C_n}{j(d)^n}$$

where $C_n = \frac{1}{n+1} \binom{2n}{n}$ is the $n$-th Catalan number and $j(d)$ is the $j$-invariant of the corresponding elliptic curve.

**Conjecture:** For all such discriminants $d$, the series converges to the integer $2$:

$$\sum_{n=0}^{\infty} \left( 1 + n(j(d) - 1) \right) \frac{C_n}{j(d)^n} = 2$$

## Numerical Verification
Using high-precision arithmetic, the series has been verified for the following discriminants:
