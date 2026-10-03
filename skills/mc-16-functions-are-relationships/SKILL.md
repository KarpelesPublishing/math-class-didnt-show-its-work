---
name: mc-16-functions-are-relationships
description: Teaches functions as dependable assignments (one output per input), fractional exponents as root then power, second differences for spotting quadratics, and how linear, quadratic and exponential patterns differ. Use when a learner asks what makes something a function, what 8 to the 2/3 means, how to tell a quadratic from a table, or the difference between linear and exponential growth.
---

# Chapter 16: Functions Are Relationships

## The core idea

A function is a dependable assignment: each allowed input gets exactly one output. Two inputs may share an output, but one input may not have two. A fractional exponent names a root (the denominator) and then a power (the numerator). Tables at equally spaced inputs reveal patterns: a constant difference marks a linear pattern, constant second differences mark a quadratic, and a constant factor marks an exponential.

## Key equations (as the chapter writes them)

- y^2 = x and y = x^2
- 8^(2/3) = (8^(1/3))^2 = 4, and 4^(1/2) x 4^(1/2) = 4^1
- q(x) = 2x^2 + 1, with second differences 2a
- f(x) = 2x + 3, g(x) = x^2, h(x) = 2^x

## Coaching method

1. Ask for the learner's own relationship (a rate table, a mapping, a growth story).
2. Predict first: "How many arrows leave each input?" or "Will the difference or the factor stay constant?"
3. Walk one substitution at a time: one input, one arrow; one root, then one power; one subtraction at a time.
4. Check with a reverse step: raise the root answer back (4^3 = 64 = 8^2), or confirm differences twice.
5. Name the domain first, so the learner knows which inputs count.

## Common sticking points

- Thinking two inputs sharing an output breaks the rule. It does not (Panel B, y = x^2).
- Missing that y^2 = x gives two outputs at input 4 (2 and -2), so it is not a function of x.
- Reading 2/3 as "two thirds of 8" (16/3). It means cube root, then square.
- Matching a table at one lucky point. Look at several steps.
- Taking a factor when an earlier output is 0. It is undefined.

## Worked example with the book's numbers

Fractional power 8^(2/3):
1. Denominator 3 means the cube root: the cube root of 8 is 2, because 2^3 = 8.
2. Numerator 2 means square it: 2^2 = 4.
3. Reverse: 4^3 = 64 and 8^2 = 64.
4. The trap: 2/3 x 8 = 16/3, which is not the power.

Second differences for q(x) = 2x^2 + 1: outputs 1, 3, 9, 19, 33. First differences 3 - 1 = 2, 9 - 3 = 6, 19 - 9 = 10, 33 - 19 = 14. Second differences 6 - 2 = 4, 10 - 6 = 4, 14 - 10 = 4, each equal to 2a = 2 x 2 = 4.

Three families at x = -2 to 2: f gives -1, 1, 3, 5, 7 (difference 2 every step); g gives 4, 1, 0, 1, 4 (differences -3, -1, 1, 3); h gives 1/4, 1/2, 1, 2, 4 (factor 2 every step).

## When the idea stops working

- Fractional powers here use positive bases only; a negative number has no real square root.
- Values that are not whole numbers (8^(1/2) is about 2.8284) are approximate.
- A finite table supports a pattern choice but cannot prove the rule at unlisted inputs.
- With a = 0 the rule is not quadratic.

## Companion notebook

See the four demonstrations with pictures in `notebooks/16-functions-are-relationships.ipynb` in this repository.
