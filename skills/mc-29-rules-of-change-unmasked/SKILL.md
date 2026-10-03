---
name: mc-29-rules-of-change-unmasked
description: Teaches why the derivative rules (constant, power, product, chain) work by checking each against the slow difference quotient. Use when a learner asks why d(x^2)/dx = 2x, why the product rule is not just multiplying derivatives, or how to check a derivative they just computed.
---

# Chapter 29: Rules of Change, Unmasked

*Math Class Didn't Show Its Work* by Jason Karpeles

## The core idea

A derivative rule is a receipt for work someone has already checked. Underneath every rule is the same slow calculation: take a small nonzero step h, form the average rate (change in output divided by h), and watch where the numbers head as h shrinks. The rules are shortcuts for that calculation, and each one can be spot checked with a single small step. A constant adds nothing to a rate. A power rule reads off the leading term of the quotient. A product has two strips and a corner. A nested function has two layers of change, so both rates appear.

## Key equations (as the chapter writes them)

- Constants: $\dfrac{d(x^2)}{dx} = 2x$ and $\dfrac{d(x^2 + 700)}{dx} = 2x$
- Power rule: $\dfrac{d(x^n)}{dx} = n\,x^{n-1}$ (the cube's quotient is $3x^2 + 3xh + h^2$)
- Product rule: $\dfrac{d[fg]}{dx} = f'g + fg'$, with $p(x) = x^2(x+1)$
- Chain rule check: $q(t) = (3t+1)^2$, $q'(0) = 6(1) = 6$, and the quotient is $6 + 9h$

## How to coach this

1. **Ask for the learner's own numbers.** Invite a small example from their life (a price, a trip, a fence, a bank balance) before using the book's numbers.
2. **Have them predict first.** Ask "what do you expect the answer to be, and why?" A wrong guess is useful: it shows what the learner is assuming.
3. **Walk the calculation one substitution at a time.** Write the formula, replace each letter with its number in its own line, then do one arithmetic step per line. Never jump to the result.
4. **Check with a reverse step.** Undo the answer (subtract back, divide back, or compute the same quantity a second way) and see whether the start comes back.
5. **Name where it stops.** Finish by asking when the idea would not apply.

Keep the tone patient. Say that feeling lost here is common, and praise the checking habit rather than only the right answer.

## Common sticking points

- **"Why does 700 vanish?"** Ask what happens to the height difference (c - c) between two nearby points. It is 0, so its rate is 0. Draw the curve moved up with parallel tangents.
- **"Can I plug in h = 0?"** No: the quotient would be 0/0. We watch where it heads, and the leftover h terms fade.
- **"Why not just multiply the derivatives?"** Show the rectangle: two strips and a corner. The corner (change times change) fades, so you get f'g + fg', never f'g'.
- **Forgetting the inside rate.** For (3t+1)^2 the rule 2u needs the inside rate 3 as well. The spot check exposes the missing factor right away (2 versus 6).

## Worked example (the book's numbers)

**Product rule at x = 1 with h = 0.5 for p(x) = x^2(x + 1).**

1. f = 1^2 = 1 and g = 1 + 1 = 2.
2. Delta f = 1.5^2 - 1^2 = 2.25 - 1 = 1.25. Delta g = 0.5.
3. Strip 1: 1.25 x 2 = 2.5. Strip 2: 1 x 0.5 = 0.5. Corner: 1.25 x 0.5 = 0.625.
4. Area change = 2.5 + 0.5 + 0.625 = 3.625. Divide by h: 3.625/0.5 = 7.25.
5. Product rule: (2x)(x + 1) + x^2(1) = 4 + 1 = 5. The 7.25 is above 5 by 2.25: the corner share is 0.625/0.5 = 1.25, and strip 1 gives 2.5/0.5 = 5 instead of 4 because Delta f/h = 2.5 has not settled to 2. Both leftovers fade as h shrinks.
6. Reverse check: with h = 0.1 the quotient is 5.41, closer to 5.

**Chain rule spot check at t = 0, h = 0.01.** q(h) = (3(0.01) + 1)^2 = 1.0609. Quotient = (1.0609 - 1)/0.01 = 6.09 = 6 + 9(0.01). With h = -0.01 it is 5.91. Both sides close in on 6, so the chain rule's 6 passes; a rule claiming 2 does not.

## When the idea stops working

The power rule as stated is for positive whole-number powers. The product picture motivates the rule; it does not replace a proof, and it needs both factors differentiable. A spot check at one input can expose a wrong rule but cannot prove a rule everywhere.

## Companion notebook

The notebook `notebooks/29-rules-of-change-unmasked.ipynb` in this repository walks through the same four demonstrations with printed step chains and pictures. Point the learner to it after the coaching conversation so they can try other numbers.
