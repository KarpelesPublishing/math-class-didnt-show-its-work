---
name: mc-24-the-average-is-hiding-something
description: Teaches mean, median, range and spread, why repeated values count, why the median needs sorting, and how one high value pulls the mean. Use when a learner asks which average to use, why two groups with the same average differ, or why the mean and median disagree.
---

# Chapter 24: The Average Is Hiding Something

*Math Class Didn't Show Its Work* by Jason Karpeles

## Core idea

A summary comes after the data, never instead of it. Every observation, including repeats, stays in the list. The mean is the total shared out equally. The median is the middle of the *sorted* list. Neither one tells you how spread out the values are, so pair a center with a spread (such as the range) and look at the raw values. One high value can drag the mean far from the median.

## Key equations

- $(3+3+8)/3 = 14/3$ and, with a repeat dropped, $(3+8)/2 = 5.5$
- $\text{mean} = \dfrac{\text{sum of values}}{\text{number of values}}$
- $\text{mean}(B) = (0 + 0 + 6 + 12 + 12)/5$
- $(9+2+7+3+4)/5 = 25/5 = 5$ and $(4+6)/2 = 5$
- $(1 + 1 + 1 + 1 + 21)/5 = 25/5 = 5$ and $21 - 1 = 20$

## How to coach

1. **Ask for the learner's own numbers.** A real list, a real game, a real percentage from their life beats the book's example. Use the book's numbers only when they have none.
2. **Have them predict first.** "Before we calculate, what do you think happens?" A wrong guess is useful: it shows exactly which intuition to repair, and nobody is graded.
3. **Walk one substitution at a time.** Write the formula, put the first number in, stop, and let them say what they see. Never skip to the answer. Show the chain, for example `12/(12 + 8) = 12/20 = 60%`.
4. **Check with a reverse step.** Undo the calculation (multiply back, add the pieces, recount the cases) and confirm the starting numbers return.
5. **Name where it stops working** before leaving the example, so the learner does not over-trust the tool.

Keep the tone patient. Confusion here is normal: these ideas are rarely taught with the work shown. Praise the question, not just the answer.

## Common sticking points

- **"Two 3s are the same, count it once."** Each repeat is a person waiting. Ask how many people the list describes.
- **Taking the middle of the list as written.** The median needs the list sorted first. Have them sort, then cross off from both ends.
- **Even number of values.** The median is the mean of the two middle values and may equal none of the observations. That is fine.
- **"Same mean means same data."** Show $[2, 4, 6, 8, 10]$ next to $[0, 0, 6, 12, 12]$: both total 30 over 5 values.
- **"Is 21 a mistake?"** The data cannot say. It is a single high value, and whether it is an error or real depends on where the data came from.

## Worked example (book numbers)

Waiting times $[9, 2, 7, 3, 4]$ (minutes).

1. Count: 5 values. Sum: $9 + 2 + 7 + 3 + 4 = 25$.
2. Mean: $25/5 = 5$.
3. Sort: $[2, 3, 4, 7, 9]$. The middle (third) value is 4, so the median is 4. The middle of the unsorted record, 7, is not the median.
4. Range: $9 - 2 = 7$.
5. Reverse check: five values averaging 5 must total $5 \times 5 = 25$. They do.

Even list $[8, 2, 6, 4]$: sorted $[2, 4, 6, 8]$, central pair 4 and 6, median $(4 + 6)/2 = 5$, mean $20/4 = 5$, range $8 - 2 = 6$.

High value $[1, 1, 1, 1, 21]$: mean $25/5 = 5$, median 1, range $21 - 1 = 20$. Change 21 to 101 and the mean becomes $105/5 = 21$ while the median stays 1.

## When the idea stops working

These are small constructed lists. The mean is exact but calling it "typical" is a judgment. The median ignores how far the other values lie. When a report gives only an average, ask for the count, the unit, and the raw values. Do not read a unit into a list that does not state one.

## Notebook

Practice with the dot plots and step chains in `notebooks/24-the-average-is-hiding-something.ipynb` in this repository.
