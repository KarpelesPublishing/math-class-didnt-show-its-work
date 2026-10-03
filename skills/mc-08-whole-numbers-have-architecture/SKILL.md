---
name: mc-08-whole-numbers-have-architecture
description: Coaches factors, primes, factor trees, exponents with signs, and square roots (Chapter 8 of Math Class Didn't Show Its Work). Use when a learner asks how to list factors, why different factor trees give the same primes, why (-3)^2 and -3^2 differ, or what a square root really undoes.
---

# Chapter 8: Whole Numbers Have Architecture

*Math Class Didn't Show Its Work* by Jason Karpeles

## The core idea in plain words

A whole number is built from smaller numbers. Its factors are the rectangles it can make. Its prime factors are the parts that cannot be split further, and they are the same no matter how you split. An exponent counts repeated copies, and a square root undoes a square.

## Key equations (as the chapter writes them)

- Factors: $36 \div 4 = 9$
- Prime factorization of 360: $360 = 2 \times 2 \times 2 \times 3 \times 3 \times 5 = 2^3 \times 3^2 \times 5$
- Signs and exponents: $(-3)^2 = (-3)(-3) = 9$, $-(3\times3) = -9$, $(-2)^3 = (-2)(-2)(-2) = 4(-2) = -8$
- Square root: $\sqrt{144} = 12$ and $144 = 2^4 \times 3^2 = (2^2 \times 3)^2 = 12^2$

## Coaching method

1. **Ask for the learner's own numbers.** A number of items to arrange in a rectangle (chairs, tiles, a calendar) or their age or house number for factoring.
2. **Have them predict first.** "How many rectangles will 13 tiles make?" "Will 50 tiles make a perfect square?"
3. **Walk one substitution at a time.** Divide by 1, 2, 3, ... and write each partner. For trees, split at whatever pair they see first, then mark prime endpoints.
4. **Check with a reverse step.** Multiply the endpoints back: 8 x 9 x 5 = 360. Square a proposed root: 12 x 12 = 144.

## Common sticking points and gentle ways through

- **"When do I stop listing factors?"** When the partners start to turn around (36 / 6 = 6 is the last new pair).
- **"My tree is different from the book's."** Good. Compare the endpoints: they always match. Stopping at a composite number such as 4 means the tree is not finished.
- **"Why is -3^2 negative?"** Circle the complete base. With no parentheses, only 3 is the base, the power is done first, and the minus waits: -(3 x 3) = -9.
- **"Is the square root of 144 equal to plus or minus 12?"** The root symbol names only the nonnegative one. Solving x^2 = 144 gives both.
- **"Is 1 prime?"** No: it has only one factor, so it is neither prime nor composite.

## Worked example with the book's numbers

Factor 360 starting from 36 x 10:

1. 36 x 10 = 360. Split 36 = 4 x 9 and 10 = 2 x 5.
2. Split 4 = 2 x 2 and 9 = 3 x 3.
3. Endpoints: 2, 2, 3, 3, 2, 5. Sorted: 2 x 2 x 2 x 3 x 3 x 5 = 2^3 x 3^2 x 5.
4. Check: 2 x 2 x 2 = 8, 3 x 3 = 9, 8 x 9 = 72, 72 x 5 = 360.

Square root of 144:

1. 144 = 2^4 x 3^2.
2. Every prime is paired: the four 2s make two pairs, and the two 3s make one pair.
3. One from each pair: 2 x 2 x 3 = 12.
4. Check: 12 x 12 = 144.

For 50 = 2 x 5^2 the 2 is unpaired, so 50 is not a perfect square: 7 x 7 = 49 and 8 x 8 = 64, so the root is between 7 and 8.

## When the idea stops working

- Factor pairs here mean positive whole numbers and positive factors. 0 is outside the definitions.
- Factor trees need a whole number greater than 1.
- Whole-number square roots exist only for perfect squares.

## Notebook

See `notebooks/08-whole-numbers-have-architecture.ipynb` in this repository for the four demonstrations with step-by-step arithmetic and pictures.
