---
name: mc-30-where-is-the-best-point
description: Teaches optimization with a fixed-perimeter rectangle: one constraint, derivative candidates, completing the square, and endpoint checks. Use when a learner asks how to find a maximum or minimum, why a zero derivative is not enough, or what to do when the turning point is outside the allowed inputs.
---

# Chapter 30: Where Is the Best Point?

*Math Class Didn't Show Its Work* by Jason Karpeles

## The core idea

The best point is never best until the question says best for what, and over which inputs. Write the objective, write the allowed inputs, reduce to one variable using the constraint, list candidates (where the slope is zero, plus endpoints), and compare values. A zero derivative says where to look; it does not certify a maximum.

## Key equations (as the chapter writes them)

- Constraint: $y = 10 - x$ (from perimeter $2x + 2y = 20$), area $A(x) = xy$
- Slope: $A'(x) = 10 - 2x$
- Completed square: $A(x) = 25 - (x - 5)^2$
- Off-limits turning point: $B'(x) = 12 - 2x$ and $B(x) = 36 - (x - 6)^2$ on $[0, 4]$

## How to coach this

1. **Ask for the learner's own numbers.** Invite a small example from their life (a price, a trip, a fence, a bank balance) before using the book's numbers.
2. **Have them predict first.** Ask "what do you expect the answer to be, and why?" A wrong guess is useful: it shows what the learner is assuming.
3. **Walk the calculation one substitution at a time.** Write the formula, replace each letter with its number in its own line, then do one arithmetic step per line. Never jump to the result.
4. **Check with a reverse step.** Undo the answer (subtract back, divide back, or compute the same quantity a second way) and see whether the start comes back.
5. **Name where it stops.** Finish by asking when the idea would not apply.

Keep the tone patient. Say that feeling lost here is common, and praise the checking habit rather than only the right answer.

## Common sticking points

- **"Why is there only one variable?"** The perimeter fixes y once x is chosen. Have the learner try x = 2 and find y and the area themselves.
- **"What does the derivative mean here?"** Slope of the area curve: positive means area is rising as x grows. Let them test x = 3, 4, 5, 6.
- **"Why trust x = 5?"** Because a second route agrees: 25 minus a square is never more than 25. Two routes agreeing is the check.
- **"The formula peaks at 6, so use 6."** Only if 6 is allowed. On [0, 4] the function is still rising, so the answer is the endpoint.

## Worked example (the book's numbers)

**Rectangle with perimeter 20.**

1. Choose x = 4. Then y = 10 - 4 = 6.
2. Perimeter check: 2(4) + 2(6) = 8 + 12 = 20.
3. Area: A(4) = 4 x 6 = 24.
4. Slope: A'(4) = 10 - 2(4) = 2, positive, so area is still rising.
5. At x = 5: A'(5) = 10 - 10 = 0 and A(5) = 25.
6. Reverse check with the completed square: A(4) = 25 - (4 - 5)^2 = 25 - 1 = 24. It matches, and A(6) = 24 too.

**Boundary case.** B(x) = 12x - x^2 on [0, 4]: B'(x) = 12 - 2x is zero at 6, which is not allowed. B(4) = 48 - 16 = 32 = 36 - (4 - 6)^2. The best allowed value is 32 at the endpoint. On the open interval (0, 4) there is no largest value: the numbers approach 32 but never reach it.

## When the idea stops working

A mathematical optimum cannot choose goals, value tradeoffs, or validate data. The model only answers the question as stated. A real rectangle needs 0 < x < 10 (at x = 10 the shape has no width). The completed-square ceiling works because a square is never negative; it would not work for a cubic.

## Companion notebook

The notebook `notebooks/30-where-is-the-best-point.ipynb` in this repository walks through the same four demonstrations with printed step chains and pictures. Point the learner to it after the coaching conversation so they can try other numbers.
