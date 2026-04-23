# Newton's Binomial Theorem

Newton's Binomial Theorem provides a formula for expanding expressions of the form $(x + y)^n$, where $n$ is a non-negative integer. It generalizes the well-known identities for $(x+y)^2$ and $(x+y)^3$ to any natural power.

## Binomial Expansion

The binomial expansion of $(x + y)^n$ is given by:

$$ (x + y)^n = \sum_{k=0}^{n} \binom{n}{k} x^{n-k} y^{k} $$

Expanding the summation explicitly:

$$ (x + y)^n = \binom{n}{0} x^{n} y^{0} + \binom{n}{1} x^{n-1} y^{1} + \binom{n}{2} x^{n-2} y^{2} + \cdots + \binom{n}{n} x^{0} y^{n} $$

Where the **binomial coefficient** is defined as:

$$ \binom{n}{k} = \frac{n!}{k!,(n-k)!} $$

### Example

For $n = 4$:

$$ (x + y)^4 = x^4 + 4x^3 y + 6x^2 y^2 + 4x y^3 + y^4 $$

---

## General Term Formula

The **general term** (also known as the $(k+1)$-th term) of the binomial expansion of $(x + y)^n$ is:

$$ T_{k+1} = \binom{n}{k} x^{n-k} y^{k} $$

Where:

- $n$ is the exponent of the binomial,
- $k$ is the index of the term, with $k = 0, 1, 2, \dots, n$,
- $T_{k+1}$ denotes the term in position $k+1$ of the expansion.

This formula allows one to find any specific term of the expansion without computing the entire sum.

### Example

To find the 4th term of $(x + y)^6$, set $k + 1 = 4$, so $k = 3$:

$$ T_{4} = \binom{6}{3} x^{6-3} y^{3} = 20, x^3 y^3 $$

---

## Stifel's Relation

**Stifel's Relation** (also known as Pascal's Rule) is a fundamental identity involving binomial coefficients, used to construct Pascal's Triangle. It states:

$$ \binom{n}{k} + \binom{n}{k+1} = \binom{n+1}{k+1} $$

Equivalently, it can be written as:

$$ \binom{n-1}{k-1} + \binom{n-1}{k} = \binom{n}{k} $$

### Interpretation

Each entry in Pascal's Triangle is the sum of the two entries directly above it. For instance:

$$ \binom{4}{1} + \binom{4}{2} = \binom{5}{2} $$

$$ 4 + 6 = 10 \quad \checkmark $$

### Proof Sketch

Starting from the definition of the binomial coefficient:

$$ \binom{n}{k} + \binom{n}{k+1} = \frac{n!}{k!(n-k)!} + \frac{n!}{(k+1)!(n-k-1)!} $$

Finding a common denominator and simplifying:

$$ = \frac{n!,(k+1) + n!,(n-k)}{(k+1)!,(n-k)!} = \frac{n!,(n+1)}{(k+1)!,(n-k)!} = \frac{(n+1)!}{(k+1)!,(n-k)!} = \binom{n+1}{k+1} $$

This confirms Stifel's Relation.

---
Back to: [[index]]