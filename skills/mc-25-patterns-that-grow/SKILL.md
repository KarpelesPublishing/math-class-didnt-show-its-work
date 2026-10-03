---
name: mc-25-patterns-that-grow
description: Teaches arithmetic versus geometric patterns, index conventions (a_0 versus a_1), and percent change as a multiplier (Chapter 25, Patterns That Grow). Use when a learner asks how to jump to the 50th term, why 10% growth is not adding 10, why a formula has n - 1 in it, or why a pattern of four numbers does not prove what comes next.
---

# Chapter 25: Patterns That Grow

From *Math Class Didn't Show Its Work* by Jason Karpeles.

## The core idea

A pattern is not a prophecy until someone says how it continues. Say where the counting starts (index 0 or index 1), and say whether each step adds the same amount or multiplies by the same amount. Then a direct rule lets you jump to any term without listing all the ones before it, and the step-by-step walk lets you check that rule.

## Key equations

- Constant difference (arithmetic): $a_n = a_0 + nd$. Example: Stack A starts at 100 and adds 10, so $a_4 = 100 + 10(4) = 140$.
- Constant multiplier (geometric): $b_n = 100(1.10)^n$. Example: $b_4 = 100(1.10)^4 = 146.41$.
- Same list, two index choices: $a_n = 7 + 4n$ (first entry is $a_0$) or $a_n = 7 + 4(n-1)$ (first entry is $a_1$).
- Percent change: new = previous + 0.10(previous), which is multiplying by 1.10. Three rounds: $100(1.10)^3 = 133.1$.

## How to coach it

1. **Ask for their own numbers.** "What is a pattern you meet in real life: a savings balance, a rent that rises, a stack of something?" Use their start value and their step.
2. **Have them predict first.** "If this adds 10 each time, roughly where is it after 4 steps? If it grows 10 percent each time, will it be higher or lower than that?" A guess makes the real answer stick.
3. **Walk one substitution at a time.** Write the rule, then replace each letter with its number on its own line: $a_4 = 100 + 10(4)$, then $= 100 + 40$, then $= 140$.
4. **Check with a reverse step.** Walk the pattern forward card by card (100, 110, 120, 130, 140) and see that it agrees with the direct rule. For growth, divide by the multiplier to step back: $146.41 / 1.10 = 133.1$.

## Common sticking points

- **"The little n is a multiplication."** It is a position label. Say "a sub 4" and point to the fifth card (index 0 is the first card).
- **Off by one.** Have them write the first index beside the first value before using any rule. Under $a_0$ the 4th entry is $a_3$; under $a_1$ it is $a_4$. Same card, same value.
- **"10% growth means add 10 each time."** Show 100, 110, 121: the second step adds 11, not 10, because the tenth is taken from the larger amount.
- **Multiplying by 0.10 instead of 1.10.** 0.10 keeps only a tenth: that is a 90 percent cut. Growth keeps the whole and adds the tenth, so the multiplier is 1.10.
- **Two decreases of 20 percent make 60.** No: each keeps 80 percent, so $100(0.8)(0.8) = 64$.

## Worked example with the book's numbers

Stack A: start 100, add 10. Stack B: start 100, multiply by 1.10. Both begin 100, 110.

1. Stack A, index 4: $a_4 = 100 + 10(4) = 100 + 40 = 140$.
2. Stack B step by step: $100 \times 1.10 = 110$; $110 \times 1.10 = 121$; $121 \times 1.10 = 133.1$; $133.1 \times 1.10 = 146.41$.
3. Stack B direct: $b_4 = 100(1.10)^4 = 146.41$. The two ways agree.
4. Compare: $146.41 - 140 = 6.41$. B's last step added 13.31, while A always adds 10. Far out the gap is large: at index 10, $a_{10} = 200$ and $b_{10}$ is about 259.37.
5. Reverse check: $146.41 / 1.10 = 133.1$, one step back.

## When the idea stops working

- Four cards do not prove how a pattern continues. The rule has to be declared or justified, not guessed from a few terms.
- The arithmetic rule needs the same difference at every step; the geometric rule needs the same multiplier at every step.
- If the percent is always taken from the original amount rather than the current amount, the pattern is arithmetic, not geometric.

## Practice to offer

- Using $a_n = 100 + 10n$, find $a_9$ (answer 190).
- Find $b_5$ for Stack B (answer 161.051).
- Apply a 20 percent decrease twice to 100 (answer 64).

## Notebook

For a guided walk with pictures, open `notebooks/25-patterns-that-grow.ipynb` in this repository.
