# Recursion

Method where the solution depends on solutions to smaller instances of the same problem.
Recursive function has one or more base cases, and one or more recursive cases.

Example of recursive procedures:

- Factorial
- Greatest common divisor
- Tower of Hanoi
- Binary search

Example of recursive data structures:

- Linked List
- Binary Tree

## Tail vs Augmenting

- Tail-recursion: recursive call at the end without any additional operations (i.e. gcd function)
- Augmenting-recursion: recursive call not in tail position. Its result is combined in a deferred way when the last recursive call is completed.

## Algorithms

### Divide and conquer

Divide a problem into sub-problem of the same type as the original, solve those sub-problems and combine the results.

### Dynamic programming

Results of sub-problems are stored in a lookup table.
