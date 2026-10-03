---
name: mc-15-a-graph-is-a-story
description: Teaches graphs as reports of two quantities at once: domains and the spaces between tick marks, slope from two points, intercepts and what they mean, and where two lines cross. Use when a learner asks whether to connect the dots, how to find slope without sign errors, whether an intercept matters, or what an intersection means.
---

# Chapter 15: A Graph Is a Story

## The core idea

A graph reports two quantities at once, and its labels, domain and scale are part of the story. The domain decides whether points join into a line. Slope is vertical change over horizontal change, with both changes taken from the same start to the same end. An intercept is where a graph meets an axis, and it only means something if its input lies in the domain. An intersection means equal output from two rules at the same input.

## Key equations (as the chapter writes them)

- d(t) = 12 - 3t, and 12 - 3(0.5) = 10.5
- (5 - (-3)) / (-2 - 2) = 8 / (-4) = -2, and -8 / 4 = -2
- 0 = 2x + 3, so x = -3/2
- A(x) = B(x): 2x + 3 = x + 7, crossing at (4, 11)

## Coaching method

1. Ask for the learner's own graph or two points (a trip, a savings plan, a price chart).
2. Predict first: "Does the line fall or rise? So is the slope positive or negative?"
3. Walk one substitution at a time: write both changes with the same start and end labels, keep negatives in parentheses, then divide.
4. Check with a reverse step: test a third point on the line, or put the crossing input into both rules.
5. Always ask: what are the allowed inputs, and what do the axis labels say?

## Common sticking points

- Reversing the order in only the top or only the bottom, flipping the sign. If the line falls, the slope must be negative.
- Joining dots when the inputs are counts. Ask whether 0.5 is a legal input.
- Reading an intercept as meaningful outside the domain. (-3/2, 0) is a fact about the line, not about the plan.
- Treating a vertical line's slope as zero. It is undefined (division by zero).
- Reading a crossing off a graph as exact. Substitute into both rules.

## Worked example with the book's numbers

Slope from (-2, 5) to (2, -3):
1. Vertical change: -3 - 5 = -8.
2. Horizontal change: 2 - (-2) = 4.
3. Slope = -8 / 4 = -2.
4. Reverse the order of both: (5 - (-3)) / (-2 - 2) = 8 / (-4) = -2. Same.
5. Mixed order: -8 / (-4) = +2, which is wrong for a falling line.

Crossing: A(4) = 2(4) + 3 = 11 and B(4) = 4 + 7 = 11. Solve 2x + 3 = x + 7: subtract x to get x + 3 = 7, then x = 4. At x = 2, A = 7 and B = 9; at x = 6, A = 15 and B = 13.

## When the idea stops working

- A line between tick marks is only part of the story if those inputs are allowed.
- An intercept outside the plan domain (0 to 6) has no meaning in the plan.
- The example rules are invented, so a larger output is not "better" until the story says what the output means.

## Companion notebook

See the four demonstrations with pictures in `notebooks/15-a-graph-is-a-story.ipynb` in this repository.
