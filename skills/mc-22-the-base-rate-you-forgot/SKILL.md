---
name: mc-22-the-base-rate-you-forgot
description: Teaches how to read a percentage by asking "among which group?", build a two by two count table, split a population by its base rate, and see why most positive results can be false. Use when a learner is confused by test accuracy, false positives, conditional probability, or why two true percentages seem to disagree.
---

# Chapter 22: The Base Rate You Forgot

*Math Class Didn't Show Its Work* by Jason Karpeles

## Core idea

A percentage is only half a sentence until you say which group it is a percentage of. The word "among" (or "given") names the denominator. Build a table of counts first, outline the group you are asking about, and divide the part by that group's total. Before any test, the base rate splits the population into two very different sized groups, and a small error rate applied to the big group can outnumber a large success rate applied to the small group.

## Key equations

- $P(D \mid A)$: probability of damage given an alert; the group after the bar is the denominator
- Population split: $10{,}000 - 100 = 9{,}900$
- $\text{sensitivity} = 90/(90 + 10)$
- $\text{positive predictive value} = 90/(90 + 495)$
- $P(\text{condition} \mid \text{positive}) = 90/585 = 2/13$, about $15.4\%$

## How to coach

1. **Ask for the learner's own numbers.** A real list, a real game, a real percentage from their life beats the book's example. Use the book's numbers only when they have none.
2. **Have them predict first.** "Before we calculate, what do you think happens?" A wrong guess is useful: it shows exactly which intuition to repair, and nobody is graded.
3. **Walk one substitution at a time.** Write the formula, put the first number in, stop, and let them say what they see. Never skip to the answer. Show the chain, for example `12/(12 + 8) = 12/20 = 60%`.
4. **Check with a reverse step.** Undo the calculation (multiply back, add the pieces, recount the cases) and confirm the starting numbers return.
5. **Name where it stops working** before leaving the example, so the learner does not over-trust the tool.

Keep the tone patient. Confusion here is normal: these ideas are rarely taught with the work shown. Praise the question, not just the answer.

## Common sticking points

- **"The test is 90% accurate, so a positive means 90%."** Ask: 90% of which group? Sensitivity is across the condition row. A positive result lives in the positive column, which has a different total.
- **Mixing up "A given D" with "D given A".** Have them outline the row or column in the table and say the denominator aloud.
- **"Where do the false positives come from?"** From the big group. Compute 5% of 9,900 and compare it with 90.
- **Decimals and percentages feel slippery.** Use counts of people (natural frequencies): "495 people", not "0.05". Counts keep the groups visible.
- **Does doubling the population change the answer?** No: both numerator and denominator double. Let them compute it to see $180/1{,}170 = 2/13$.

## Worked example (book numbers)

Audit of 100 parcels: 12 damaged and alerted, 3 damaged and not alerted, 8 sound and alerted, 77 sound and not alerted. Check: $12 + 3 + 8 + 77 = 100$.

1. Among damaged parcels: $12/(12 + 3) = 12/15 = 80\%$.
2. Among alerted parcels: $12/(12 + 8) = 12/20 = 60\%$.
3. Among sound parcels: $8/(8 + 77) = 8/85 = 9.4\%$.

Same table, three denominators, three true percentages.

Now the 10,000-person model (fictional): base rate 1%, sensitivity 90%, false-positive rate 5%.

1. With the condition: $1\% \times 10{,}000 = 100$. Without: $10{,}000 - 100 = 9{,}900$.
2. True positives: $90\% \times 100 = 90$. False negatives: $100 - 90 = 10$.
3. False positives: $5\% \times 9{,}900 = 495$. True negatives: $9{,}900 - 495 = 9{,}405$.
4. All positives: $90 + 495 = 585$.
5. $P(\text{condition} \mid \text{positive}) = 90/585 = 2/13 \approx 15.4\%$.
6. Reverse check: $90 + 10 + 495 + 9{,}405 = 10{,}000$.

At a 2% base rate: $180/(180 + 490) = 180/670 = 18/67 \approx 26.9\%$. Doubling the base rate gave less than double the share.

## When the idea stops working

The table needs the base rate to belong to the same population being tested, and sensitivity and false-positive rate must be held fixed when the base rate changes. The numbers are fictional and describe no real condition, test, or diagnosis. Scaling a table works only when every cell is multiplied by the same factor.

## Notebook

Practice with the tables and step chains in `notebooks/22-the-base-rate-you-forgot.ipynb` in this repository.
