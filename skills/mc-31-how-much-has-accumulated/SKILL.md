---
name: mc-31-how-much-has-accumulated
description: Teaches accumulation: rate times duration, signed contributions, net change versus total magnitude, and rectangle sums with different sampling rules and unequal widths. Use when a learner asks what an integral adds up, why areas below the axis count negative, or how to estimate a total from a changing rate.
---

# Chapter 31: How Much Has Accumulated?

*Math Class Didn't Show Its Work* by Jason Karpeles

## The core idea

The gauge reports the rate; the running total keeps the receipts. A rate (units per hour) times a duration (hours) gives a change in units. Blocks below the baseline contribute negatively. For a changing rate, build rectangles whose height is the rate at a chosen sample time and whose width is that piece's own duration, then add.

## Key equations (as the chapter writes them)

- Constant-rate blocks: $6 + (-1) = 5$ units, then $10 + 5 = 15$ units
- Net change versus magnitude: $6 - 1 = 5$ and $6 + 1 = 7$
- Rising rate $r(t) = t$: sum of $r(t_i^*)\,\Delta t_i$
- Unequal widths, $r(t) = 2t$: $2.5(0.5) + 4.5(1.5) = 1.25 + 6.75 = 8$

## How to coach this

1. **Ask for the learner's own numbers.** Invite a small example from their life (a price, a trip, a fence, a bank balance) before using the book's numbers.
2. **Have them predict first.** Ask "what do you expect the answer to be, and why?" A wrong guess is useful: it shows what the learner is assuming.
3. **Walk the calculation one substitution at a time.** Write the formula, replace each letter with its number in its own line, then do one arithmetic step per line. Never jump to the result.
4. **Check with a reverse step.** Undo the answer (subtract back, divide back, or compute the same quantity a second way) and see whether the start comes back.
5. **Name where it stops.** Finish by asking when the idea would not apply.

Keep the tone patient. Say that feeling lost here is common, and praise the checking habit rather than only the right answer.

## Common sticking points

- **"Why can't I just add the rate to the amount?"** Units differ. Multiply by hours first.
- **"Which answer is right, 5 or 7?"** Both. Ask: do you want where you ended up (net) or how much happened (magnitude)?
- **"Left and right give different answers."** On a rising rate, left samples are low and right samples are high. Midpoint balances them on a straight line.
- **Using one width for everything.** If pieces have different widths, each rate must be multiplied by its own width.

## Worked example (the book's numbers)

**Two blocks from a start of 10 units.**

1. First block: 3 units per hour for 2 hours: 3 x 2 = 6 units.
2. Second block: -1 unit per hour for 1 hour: (-1) x 1 = -1 unit.
3. Net change: 6 + (-1) = 5 units.
4. Ending amount: 10 + 5 = 15 units.
5. Reverse check: 15 - 5 = 10, the start.
6. Total magnitude (a different question): 6 + 1 = 7 units.

**Unequal widths for r(t) = 2t on the partition 1, 1.5, 3 (midpoints).** Widths 0.5 and 1.5. Midpoints 1.25 and 2.25, rates 2.5 and 4.5. Sum: 2.5(0.5) + 4.5(1.5) = 1.25 + 6.75 = 8 units. Check with the average rate: 4 x 2 hours = 8. With left endpoints: 2(0.5) + 3(1.5) = 5.5, which is below 8.

## When the idea stops working

Each rectangle is exact only if the rate is constant on it. For a straight-line rate the midpoint sum is exact; for a curved rate it is only an estimate. The left-low, right-high pattern needs an increasing rate. Large opposite-sign pieces can hide a lot of activity behind a small net change.

## Companion notebook

The notebook `notebooks/31-how-much-has-accumulated.ipynb` in this repository walks through the same four demonstrations with printed step chains and pictures. Point the learner to it after the coaching conversation so they can try other numbers.
