---
name: mc-32-the-speedometer-meets-the-odometer
description: Teaches the link between a rate and its accumulation: displacement versus distance, the slope of an accumulation function, antiderivatives, endpoint subtraction, and velocities that cross zero. Use when a learner asks why integrating velocity gives position, what the Fundamental Theorem of Calculus says, or why distance and displacement differ.
---

# Chapter 32: The Speedometer Meets the Odometer

*Math Class Didn't Show Its Work* by Jason Karpeles

## The core idea

One accumulated quantity keeps direction (displacement, where you ended up). The other records every bit of movement (distance, the odometer). Accumulating a continuous rate creates a function whose slope at each moment is that rate. So to find a total, find an antiderivative, check it by differentiating, and subtract its values at the two ends. When the rate changes sign, split at the zero and add the sizes of the pieces for distance.

## Key equations (as the chapter writes them)

- Two ledgers: $+3 + (-2) = +1$ unit and $|{+3}| + |{-2}| = 3 + 2 = 5$ units
- Accumulation slope: $A'(x) = f(x)$ for $f(t) = 2t + 1$
- Antiderivative: $F(t) = t^2 + t$ with $F'(t) = 2t + 1 = v(t)$, so $F(3) - F(0) = 12$
- Sign change: $v(t) = 2t - 4$ and $F(t) = t^2 - 4t$

## How to coach this

1. **Ask for the learner's own numbers.** Invite a small example from their life (a price, a trip, a fence, a bank balance) before using the book's numbers.
2. **Have them predict first.** Ask "what do you expect the answer to be, and why?" A wrong guess is useful: it shows what the learner is assuming.
3. **Walk the calculation one substitution at a time.** Write the formula, replace each letter with its number in its own line, then do one arithmetic step per line. Never jump to the result.
4. **Check with a reverse step.** Undo the answer (subtract back, divide back, or compute the same quantity a second way) and see whether the start comes back.
5. **Name where it stops.** Finish by asking when the idea would not apply.

Keep the tone patient. Say that feeling lost here is common, and praise the checking habit rather than only the right answer.

## Common sticking points

- **"I moved 5 but I'm only 1 away."** Draw the position path: up 3, then back 2. Position keeps signs; the odometer does not.
- **"Why does adding a constant to F not matter?"** Both endpoint values shift together, so the subtraction cancels it.
- **"Why subtract?"** F(end) - F(0) is the rise of the running total, which is the accumulated change.
- **"Why is distance not just F(end) - F(0)?"** If velocity changes sign, the negative piece cancels part of the positive one. Split at the zero and flip the negative piece.

## Worked example (the book's numbers)

**Velocity v(t) = 2t - 4 m/s, starting at 10 m, stopping at t = 5.**

1. F(t) = t^2 - 4t. Check: F'(t) = 2t - 4 = v(t).
2. F(5) = 5^2 - 4(5) = 25 - 20 = 5. F(0) = 0. Displacement: 5 - 0 = 5 m.
3. Velocity is zero at t = 2. F(2) = 4 - 8 = -4.
4. Negative piece, sign flipped: -[F(2) - F(0)] = -[(-4) - 0] = 4 m.
5. Positive piece: F(5) - F(2) = 5 - (-4) = 9 m.
6. Distance: 4 + 9 = 13 m.
7. Ending position: 10 + 5 = 15 m.
8. Reverse check: the net of the pieces, -4 + 9 = 5, matches the displacement.

## When the idea stops working

The theorem needs a continuous rate on a closed interval, and one line of motion with a chosen direction. A zero of the velocity is only a candidate for a reversal: the sign on each side decides. Distance equals displacement only when the velocity never changes sign. For a curved rate, the strip divided by h is not exactly f(x) + h, though the gap still shrinks.

## Companion notebook

The notebook `notebooks/32-the-speedometer-meets-the-odometer.ipynb` in this repository walks through the same four demonstrations with printed step chains and pictures. Point the learner to it after the coaching conversation so they can try other numbers.
