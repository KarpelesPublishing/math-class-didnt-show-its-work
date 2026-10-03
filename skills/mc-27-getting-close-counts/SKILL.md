---
name: mc-27-getting-close-counts
description: Teaches partial sums, geometric series and the condition |r| < 1, meeting a tolerance and staying within it, and the three-part check for continuity (Chapter 27, Getting Close Counts). Use when a learner asks what a limit really means, why a formula for an infinite sum sometimes gives nonsense, or how to tell a hole from a jump on a graph.
---

# Chapter 27: Getting Close Counts

From *Math Class Didn't Show Its Work* by Jason Karpeles.

## The core idea

Getting close is not the same as giving up before you arrive. A limit is a promise about a gap: name any small size, and after some stage the gap is smaller than that size and stays smaller. A shortcut formula for an infinite sum comes with a condition, and continuity at a point is three checks, not a feeling about a graph.

## Key equations

- Half-distance path: $S_n = 1 - \dfrac{1}{2^n}$, and the gap is $1 - S_n = \dfrac{1}{2^n}$.
- Geometric sum: $\dfrac{a}{1 - r}$, valid only when $|r| < 1$.
- Why it works: $S_n - rS_n = a - ar^n$. The gap from the limit after $n$ terms is $\dfrac{ar^n}{1 - r}$.
- Continuity example: $f(x) = \dfrac{x^2 - 1}{x - 1}$ and $g(x) = x + 1$.

## How to coach it

1. **Ask for their own numbers.** "Pick a starting amount $a$ and a shrink factor $r$ between -1 and 1, and a gap size you would call close enough." Use theirs.
2. **Have them predict first.** "After 5 moves of half the remaining distance, will you have reached 1? How much will be left?"
3. **Walk one substitution at a time.** Write each partial sum on its own line with common denominators, then the gap, then the formula check.
4. **Check with a reverse step.** Gap plus sum should return the limit: $\frac{31}{32} + \frac{1}{32} = 1$. For the tail formula, compare it with the limit minus the partial sum.

## Common sticking points

- **"Infinitely many positive pieces must add to infinity."** Not if the pieces shrink fast enough. Show $\frac12 + \frac14 + \frac18$: each piece is half the remaining gap.
- **Using $a/(1-r)$ for any $r$.** With $r = 2$ the formula gives $-\frac12$ for a sum of positive terms. That is the signal that the condition $|r| < 1$ failed.
- **"Close once is close enough."** Convergence means the gap stays below the request for every later stage, not only one.
- **Cancelling in $\frac{x^2-1}{x-1}$ at $x = 1$.** The factoring is valid for $x \ne 1$. At $x = 1$ the original expression is $0/0$, so $f(1)$ has no value, but the nearby outputs approach 2.

## Worked example with the book's numbers

Series $3 + \frac34 + \frac{3}{16} + \cdots$ with $a = 3$, $r = \frac14$.

1. Limit: $\frac{3}{1 - 1/4} = \frac{3}{3/4} = 4$.
2. After 3 terms: $3 + \frac34 + \frac{3}{16} = \frac{48}{16} + \frac{12}{16} + \frac{3}{16} = \frac{63}{16}$. Left over: $4 - \frac{63}{16} = \frac{1}{16}$.
3. Tail formula agrees: $\frac{3(1/4)^3}{3/4} = \frac{3/64}{3/4} = \frac{1}{16}$.
4. Request: gap below 0.01. At $n = 4$ the gap is $\frac{1}{64}$, about 0.01563, not below. At $n = 5$ it is $\frac{1}{256}$, about 0.00391, below. Each later gap is the previous times $\frac14$, so it stays below.
5. Reverse check: $\frac{1}{256} \times 4 = \frac{1}{64}$, the previous gap.

Continuity at $x = 1$ for $f(x) = \frac{x^2-1}{x-1}$: at $x = 0.9$, $0.9 + 1 = 1.9$; at $x = 1.1$, $1.1 + 1 = 2.1$. Both sides head to 2, but $f(1)$ is undefined, so condition 1 fails. Defining $f(1) = 2$ fills the hole.

## When the idea stops working

- The geometric formula needs $|r| < 1$. With $r = 1$ the terms never shrink; with $r = 2$ they grow.
- The half-distance path is an idealized sum, not a claim about real distances or devices.
- Sampling a few points near $a$ is evidence, not proof. The factoring (or the definition) is what covers every nearby input.
- A jump (two sides approach 0 and 2), a hole (no value), and a moved point (limit 3 but value 8) each fail a different one of the three conditions.

## Practice to offer

- $S_5$ and its gap for the half-distance path (31/32 and 1/32).
- With $a = \frac12$, $r = -\frac12$: $S_1, S_2, S_3$ and $a/(1-r)$ (1/2, 1/4, 3/8 and 1/3).
- With $a = 3$, $r = \frac14$: sum after 3 terms and what is left (63/16 and 1/16).
- $f(0.99)$ for the hole function (1.99), and the value that fills it (2).

## Notebook

For a guided walk with pictures, open `notebooks/27-getting-close-counts.ipynb` in this repository.
