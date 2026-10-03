---
name: mc-21-random-is-not-the-same-as-equal
description: Teaches how to build a sample space, count equally likely outcomes, keep probabilities between 0 and 1, and tell independent trials from drawing without replacement. Use when a learner asks why 7 is the most likely dice sum, whether a coin is "due", why probabilities add to 1, or how drawing items changes the next chance.
---

# Chapter 21: Random Is Not the Same as Equal

*Math Class Didn't Show Its Work* by Jason Karpeles

## Core idea

Random does not mean every pattern takes turns. Build a model first: list the outcomes, check that they are equally likely, and only then count the ones that belong to the event. A tidy row of labels (the sums 2 through 12) is not a list of equally likely outcomes. The 36 ordered pairs of two dice are.

## Key equations

- Probability bounds: $0 \le P(E) \le 1$
- More than 4 on one die: $2/6 = 1/3$, and its complement $4/6 = 2/3$
- Two dice: $6 \times 6 = 36$ ordered pairs, so $P(\text{sum } 7) = 6/36 = 1/6$
- Bag of 2 red and 1 blue: $P(\text{red}) = 2/3$; after a red is kept out, $P(\text{red}) = 1/2$
- Three flips: $2 \times 2 \times 2 = 8$ paths, each $(1/2)(1/2)(1/2) = 1/8$

## How to coach

1. **Ask for the learner's own numbers.** A real list, a real game, a real percentage from their life beats the book's example. Use the book's numbers only when they have none.
2. **Have them predict first.** "Before we calculate, what do you think happens?" A wrong guess is useful: it shows exactly which intuition to repair, and nobody is graded.
3. **Walk one substitution at a time.** Write the formula, put the first number in, stop, and let them say what they see. Never skip to the answer. Show the chain, for example `12/(12 + 8) = 12/20 = 60%`.
4. **Check with a reverse step.** Undo the calculation (multiply back, add the pieces, recount the cases) and confirm the starting numbers return.
5. **Name where it stops working** before leaving the example, so the learner does not over-trust the tool.

Keep the tone patient. Confusion here is normal: these ideas are rarely taught with the work shown. Praise the question, not just the answer.

## Common sticking points

- **"There are 11 sums, so each is 1/11."** Ask them to list the ways to make 2 and the ways to make 7. Let them find (1, 1) alone versus six pairs. Then the 36-cell grid makes the point on its own.
- **"(2, 5) and (5, 2) are the same."** Imagine one red die and one blue die. They are different outcomes because the dice are different.
- **"Tails came up four times, so heads is due."** The flips do not remember. Independent trials do not take turns; the stated chance stays the same on every flip.
- **"The token is gone but the chance is the same."** Have them draw the bag as it is now. Count what remains before dividing.
- **Probability above 1 or below 0.** Treat it as a signal to recount: something was left out, counted twice, or divided by the wrong total.

## Worked example (book numbers)

Question: two fair dice, what is the chance of a sum of 7?

1. Build the sample space: $6 \times 6 = 36$ equally likely ordered pairs.
2. List the pairs with sum 7: (1, 6), (2, 5), (3, 4), (4, 3), (5, 2), (6, 1). That is 6 pairs.
3. Each pair has chance $(1/6)(1/6) = 1/36$.
4. $P(\text{sum } 7) = 6 \times 1/36 = 6/36 = 1/6$.
5. Reverse check: sums 2 through 12 have $1, 2, 3, 4, 5, 6, 5, 4, 3, 2, 1$ pairs, and $1 + 2 + 3 + 4 + 5 + 6 + 5 + 4 + 3 + 2 + 1 = 36$. Every pair is accounted for.

Second example (bag): two red, one blue. $P(\text{red}) = 2/3$. A red is kept out, leaving 1 red and 1 blue, so $P(\text{red on draw 2}) = 1/2$. If a blue is kept out instead, 2 red remain, so the chance is $2/2 = 1$. If the token is put back, the bag is restored and the chance is $2/3$.

## When the idea stops working

Counting favorable over total needs equally likely outcomes: a spinner that is three quarters blue breaks it. Two dice that are linked, or a bent coin, make the 36 pairs or the 8 paths unequal. A bag that is not mixed after a token is returned breaks the $2/3$.

## Notebook

Practice with the pictures and step chains in `notebooks/21-random-is-not-the-same-as-equal.ipynb` in this repository.
