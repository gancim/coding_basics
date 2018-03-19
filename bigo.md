# Computational Cost - Big O notation

Big O is the asymptotic runtime, expressed as function of the size of the inputs, n (operations x elements).
It is used to describe the execution time required or the space used (in memory or disk) by an algorithm.
It is machine independent.

- Big O describes the worst-case scenario
- Big Omega describes the best-case scenario

## General rules

- Ignore constants (i.e. `5n -> O(n)`)
- Certain terms dominate others
  `O(1) < O(log n) < O(n) < O(n log n) < O(n^2) < O(2^n) < O(n!) `

## Type of complexity:

0) Constant time `(1)` -> independent of input size n
1) Logarithmic `(log n)` -> inverse operation to exponentiation (i.e. binary search)
2) Linear -> `n` (i.e. for loop)
3) Quadratic -> `n^2` (i.e. two for loops)
4) Polynomial -> `n^z` (i.e. fibonacci is 2^n)
5) Exponential -> `a^n`
