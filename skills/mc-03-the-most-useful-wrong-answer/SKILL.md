---
name: mc-03-the-most-useful-wrong-answer
description: Teaches how to test a claim with counterexamples, why a claim has a domain, how a conjecture differs from a proof, and how counting leftovers explains why two odd numbers sum to an even one. Use when a learner asks how to disprove a claim, whether examples prove something, or why a true calculation might not refute a statement.
---

# Chapter 3: The Most Useful Wrong Answer

*Math Class Didn't Show Its Work* by Jason Karpeles

## The core idea

A counterexample is a case the claim allowed, with correct arithmetic, whose result conflicts with the claim. It points at the sentence that promised too much, never at the person who wrote it. Many agreeing examples are evidence, not proof. A reason that covers every case does more than any pile of examples.

## Key equations (as the chapter writes them)

- $7 \times 0 = 0$ against "multiplication always makes a number bigger"
- $1 \times 1 = 1$ and $2 \times 2 = 4 > 2$ in the squaring claims
- $1 + 3 + 5 + 7 = 16$ for the odd numbers that build squares
- $5 + 3 = 8$ for two odd rows of tiles

## Coaching method

1. **Ask for their numbers.** Start with the learner's own example, or offer one from the book. Never hand over a finished answer first.
2. **Have them predict.** Before any calculation, ask: "What do you expect will happen?" A wrong guess is useful information, not a failure.
3. **Walk one substitution at a time.** Write the equation, replace one symbol with its number, say the result, then move to the next. Do not skip lines, and do not narrate a result without showing the step that produced it.
4. **Check with a reverse step.** Finish by working backward, or by a second route, and see whether it lands on the same place.
5. **Name where it stops working.** Every idea in this chapter has a boundary. Say it out loud so the learner knows when to trust the idea.

## Common sticking points

- **"But the arithmetic is right."** Correct arithmetic is only the second of three checks. Ask: is the case allowed by the claim's domain? Does the result conflict?
- **"Does a counterexample mean I was stupid?"** No. Say it directly: it improves the sentence, and the repaired claim is better than the original.
- **"Ten examples worked, so it's true."** Ask what would be different if the claim were false. Zero and one are the first cases to try when a sentence says always.
- **Strictly larger.** "Larger" means strictly larger. Equal is not larger, so $1 \times 1 = 1$ conflicts with "larger."
- **Parity feels like memorization.** Replace the memorized rule with leftovers: odd means pairs plus one leftover.

## Worked example with the book's numbers

Test "for every whole number, squaring gives a larger number" at $n = 1$.

1. Arithmetic: $1 \times 1 = 1$. Correct.
2. Allowed? The claim says every whole number, so 1 is allowed.
3. Conflict? Is $1 > 1$? No. So this is a counterexample.

Now test the repaired claim "for whole numbers greater than one" at $n = 1$.

1. Arithmetic: $1 \times 1 = 1$. Same.
2. Allowed? Is $1 > 1$? No. The case is outside the domain.
3. So it is not a counterexample to the repaired claim, and the repaired claim is tested at 2 and 3: $2 \times 2 = 4 > 2$ and $3 \times 3 = 9 > 3$.

Then explain parity: $5 = 2 \times 2 + 1$ and $3 = 1 \times 2 + 1$. Pairs: $2 + 1 = 3$. Leftovers: $1 + 1 = 2$, which join into one more pair. So $5 + 3 = 8 = 4 \times 2 + 0$, even. Reverse step: try $7 + 9$ and get $16$, also even.

## When the idea stops working

- Whole numbers only, and "larger" means strictly larger. Say "at least as large" and 0 and 1 stop being counterexamples.
- A counterexample must be allowed by the claim as written.
- A pattern that fits every checked example (the odd-number sums 4, 9, 16, 25) is a conjecture. A structural reason, like the L-shape wrapping each square, is what moves it toward proof.

## Go further

Use the notebook at `notebooks/03-the-most-useful-wrong-answer.ipynb` in this repository. It tests the claims case by case, draws the squares built from odd numbers, and counts leftovers.
