---
name: mc-28-what-is-happening-right-now
description: Teaches average rate, the difference quotient with h never zero, secants approaching a tangent direction, and why a corner has no single rate (Chapter 28, What Is Happening Right Now?). Use when a learner asks what a derivative really is, how speed at one instant can mean anything, why h cannot just be set to zero, or why |x| has no derivative at 0.
---

# Chapter 28: What Is Happening Right Now?

From *Math Class Didn't Show Its Work* by Jason Karpeles.

## The core idea

An average can tell what happened over an interval. It cannot tell what was happening at one moment. To talk about one moment, compute honest average rates over shorter and shorter nonzero intervals, simplify, and ask what the results approach.

## Key equations

- Average rate: $\dfrac{f(b) - f(a)}{b - a}$, which is slope = vertical change / horizontal change.
- Position model: $s = t^2$ (meters, seconds).
- Difference quotient at $t = 2$: $\dfrac{s(2+h) - s(2)}{h} = \dfrac{h(4+h)}{h} = 4 + h$, valid for $h \ne 0$.
- Tangent estimate: change is about $4h$ near $t = 2$; for $h = 0.1$, $4(0.1) = 0.4$.
- Corner of $|x|$: $\dfrac{g(h) - g(0)}{h} = \dfrac{|h|}{h}$, equal to 1 for positive $h$ and $-1$ for negative $h$.

## How to coach it

1. **Ask for their own numbers.** "Give me two clock times and the position at each, or pick a second time $b$ for $s = t^2$." Use their pair.
2. **Have them predict first.** "As the interval shrinks toward zero, what do you think the average rate does? Which side of 4 will it land on for $h = -0.1$?"
3. **Walk one substitution at a time.** Write $s(2+h)$, replace $h$, square, subtract 4, divide by $h$, each on its own line.
4. **Check with a reverse step.** After dividing, multiply back: $4.1 \times 0.1 = 0.41$, the change in position. Also compare with the simplified rule $4 + h$.

## Common sticking points

- **"Just plug in $h = 0$."** That gives $0/0$, which is not a number. Simplify first with $h \ne 0$, then see what $4 + h$ approaches.
- **"Is cancelling $h$ cheating?"** It is allowed because $h$ is not zero at any stage. $h(4+h)/h = 4 + h$ holds for every nonzero $h$.
- **Signs when $b < 2$.** Both changes are negative, so the quotient stays positive: $\frac{1 - 4}{1 - 2} = \frac{-3}{-1} = 3$.
- **Units.** Meters divided by seconds gives meters per second. Say the units every time.
- **"Smooth looks the same as continuous."** $|x|$ is continuous at 0 but has a corner: the sides disagree, so there is no single rate.

## Worked example with the book's numbers

Position $s = t^2$.

1. Average rate from $t = 2$ to $t = 3$: $\frac{s(3) - s(2)}{3 - 2} = \frac{9 - 4}{1} = \frac{5}{1} = 5$ meters per second.
2. Shrink: $h = 0.1$. Second time $2 + 0.1 = 2.1$. $s(2.1) = 2.1^2 = 4.41$. Quotient $= \frac{4.41 - 4}{0.1} = \frac{0.41}{0.1} = 4.1$. Simplified rule: $4 + 0.1 = 4.1$.
3. More steps: $h = 0.5$ gives 4.5; $h = -0.1$ gives 3.9; $h = 0.01$ gives 4.01. The rates head toward 4 from both sides.
4. Tangent estimate: over $h = 0.1$ the exact change is $0.41$ m, the estimate $4(0.1) = 0.4$ m, the discrepancy $0.41 - 0.4 = 0.01$ m, which equals $h^2$.
5. Corner: $h = 0.01$ gives $\frac{|0.01|}{0.01} = 1$; $h = -0.01$ gives $\frac{0.01}{-0.01} = -1$.
6. Reverse check: $4.1 \times 0.1 = 0.41$.

## When the idea stops working

- An interval of zero width (second time equal to the first) has a zero denominator: no average rate.
- The estimate "change is about rate times step" is honest only for small steps: at $h = 1$ it is off by a whole meter.
- This chapter's model is $s = t^2$ near $t = 2$. Other motions need their own quotients.
- At a corner, one-sided rates disagree and the derivative does not exist, even though the function is continuous there.

## Practice to offer

- Average rate from $t = 2$ to $t = 4$ (6 m/s).
- Rate from $t = 2$ to $t = 2.01$ using $4 + h$ (4.01 m/s).
- At $h = 0.5$: exact change, estimate, discrepancy (2.25 m, 2 m, 0.25 m).
- $|h|/h$ at $h = -0.2$ (-1).

## Notebook

For a guided walk with pictures, open `notebooks/28-what-is-happening-right-now.ipynb` in this repository.
