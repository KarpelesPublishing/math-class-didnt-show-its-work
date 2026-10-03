---
name: mc-23-build-an-unfair-game
description: Teaches expected value as a probability-weighted average of net outcomes, how to test whether a game is fair, how to solve for a fair loss, and why equal averages can hide different spreads. Use when a learner asks how to compute expected value, whether a bet or game is fair, or why an average can be a number that never happens.
---

# Chapter 23: Build an Unfair Game

*Math Class Didn't Show Its Work* by Jason Karpeles

## Core idea

A game can smile at you while its expected value does the accounting. To find expected value, write each net outcome with its sign, multiply by its probability, and add. The result is a weighted average: a long-run balance that may be a number no single play produces. "Fair" here means an expected net value of zero. Two games can share the same expected value and still feel very different, because the average says nothing about the spread.

## Key equations

- Coin game: $E = (1/2)(2) + (1/2)(-3)$, so $E = -1/2$
- Template: $E = \tfrac14(4) + \tfrac34(-2) = 1 - \tfrac32 = -\tfrac12$
- Fair loss: $(1/4)(9) + (3/4)(-x) = 0$, which gives $9 - 3x = 0$
- Model A: $E = 1(-1) = -1$; Model B: $E = (1/2)(0) + (1/2)(-2) = -1$

## How to coach

1. **Ask for the learner's own numbers.** A real list, a real game, a real percentage from their life beats the book's example. Use the book's numbers only when they have none.
2. **Have them predict first.** "Before we calculate, what do you think happens?" A wrong guess is useful: it shows exactly which intuition to repair, and nobody is graded.
3. **Walk one substitution at a time.** Write the formula, put the first number in, stop, and let them say what they see. Never skip to the answer. Show the chain, for example `12/(12 + 8) = 12/20 = 60%`.
4. **Check with a reverse step.** Undo the calculation (multiply back, add the pieces, recount the cases) and confirm the starting numbers return.
5. **Name where it stops working** before leaving the example, so the learner does not over-trust the tool.

Keep the tone patient. Confusion here is normal: these ideas are rarely taught with the work shown. Praise the question, not just the answer.

## Common sticking points

- **Signs.** Losses are negative. Have them write "-3", not "3 lost", before multiplying.
- **"I will lose 1/2 unit next play."** No play pays that. $E$ is the long-run average per play, like a balance, not a prediction of the next result.
- **Forgetting to multiply by the probability.** Ask them to compute each contribution separately and then add. The two-bar picture (outcome, then outcome times chance) helps.
- **Fractions in the equation.** Multiply the whole equation by the common denominator (4) to clear them, then solve as usual.
- **"Same average, same game."** Ask: what is the worst single play in each? Listing outcomes shows the spread.

## Worked example (book numbers)

Fair coin, heads pays +2, tails costs 3.

1. Heads contribution: $(1/2)(2) = 1$.
2. Tails contribution: $(1/2)(-3) = -3/2$.
3. $E = 1 + (-3/2) = -1/2$ unit per play. The game is on the loss side.
4. Reverse check: a play gives $+2$ or $-3$, so the average must sit between them. $-3 < -1/2 < 2$. It does.

Fair loss with a gain of 9 at chance 1/4:

1. $(1/4)(9) + (3/4)(-x) = 0$.
2. Multiply by 4: $9 - 3x = 0$.
3. $3x = 9$, so $x = 3$.
4. Check: $(1/4)(9) + (3/4)(-3) = 9/4 - 9/4 = 0$.

A fee of 1 on every play of the gain-4, loss-2 game lowers every outcome by 1 and so lowers $E$ by exactly 1, from $-1/2$ to $-3/2$.

## When the idea stops working

Expected value describes the model's long-run average, not the next play: a short run can land anywhere. It compares centers only; choosing between two games with the same $E$ needs spread, preferences, and facts the model does not contain. Fair means zero expected net value and does not price any real game or product.

## Notebook

Practice with the bar pictures and step chains in `notebooks/23-build-an-unfair-game.ipynb` in this repository.
