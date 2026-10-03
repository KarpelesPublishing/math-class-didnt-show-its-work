---
name: mc-01-you-already-do-mathematics
description: Teaches that sorting becomes mathematics once the rule is public enough for someone else to test (sets, rules, intersection, union, complement, universe). Use when a learner asks why a classification feels arbitrary, how to write a rule, what a set is, or how "and", "or" and "not" divide a collection.
---

# Chapter 1: You Already Do Mathematics

*Math Class Didn't Show Its Work* by Jason Karpeles

## The core idea

You already sort things all day: which message to trust, which number "doesn't belong." That sorting becomes mathematics the moment the rule behind it is written clearly enough that a stranger could apply it and get the same answer. Each item gets the same yes-or-no question. A list records what happened at one moment; a rule keeps working when the situation changes.

## Key equations (as the chapter writes them)

- The opening numbers and a cube: $4, 6, 8, 9$ and $8 = 2 \times 2 \times 2$
- A set written by a list: $\{3, 6, 9, 12\}$
- Two overlapping rules on six cards: $K = \{A, C, D\}$ and $K \cap C = \{C\}$
- Two rules on a small universe: $E = \{2, 4, 6\}$ and $G = \{5, 6, 7\}$

$K$ is the set of cards from a listed contact, $C$ the cards asking for a code, $\cap$ means "in both", and $U$ (the universe) is the full collection being sorted.

## Coaching method

1. **Ask for their numbers.** Start with the learner's own example, or offer one from the book. Never hand over a finished answer first.
2. **Have them predict.** Before any calculation, ask: "What do you expect will happen?" A wrong guess is useful information, not a failure.
3. **Walk one substitution at a time.** Write the equation, replace one symbol with its number, say the result, then move to the next. Do not skip lines, and do not narrate a result without showing the step that produced it.
4. **Check with a reverse step.** Finish by working backward, or by a second route, and see whether it lands on the same place.
5. **Name where it stops working.** Every idea in this chapter has a boundary. Say it out loud so the learner knows when to trust the idea.

## Common sticking points

- **"But 4 is the odd one out too."** Yes. Several rules can pick different numbers. The skill is not finding the one right answer, it is stating the rule so the choice can be tested. Ask: "Which yes-or-no question did you use?"
- **"Why does the list have to change?"** Move the boundary and show it. The rule keeps up; the written list does not.
- **Confusing "or" with "exactly one".** In math, "in K or in C" includes cards in both. Have them list each card's two answers in a small table first.
- **What is "outside"?** Outside of what? Without a stated universe, "not in K" has no edge. Always name $U$.
- **Empty overlap feels like a mistake.** An empty set is a real answer. Show G with boundary 7: nothing qualifies, and that is fine.

## Worked example with the book's numbers

Sort $U = \{2, 3, 4, 5, 6, 7\}$ with $E$ = even numbers and $G$ = numbers greater than 4.

1. Is each number even? 2 yes, 3 no, 4 yes, 5 no, 6 yes, 7 no. So $E = \{2, 4, 6\}$.
2. Is each number greater than 4? 2 no, 3 no, 4 no (4 > 4 is false), 5 yes, 6 yes, 7 yes. So $G = \{5, 6, 7\}$.
3. In both: 6 is even and $6 > 4$. Overlap $= \{6\}$.
4. Neither: 3 is odd and $3 > 4$ is false. Outside both $= \{3\}$.
5. E only $= \{2, 4\}$ (2 numbers), G only $= \{5, 7\}$ (2 numbers).
6. Check: $1 + 2 + 2 + 1 = 6$. Every number has exactly one place.

Reverse step: the six numbers should all appear once. They do.

Then change one word: "at least 4" instead of "greater than 4". Now $G = \{4, 5, 6, 7\}$ and the overlap is $\{4, 6\}$. Exact wording moves numbers.

## When the idea stops working

- Only the stated universe is tested. Outside it, the rule says nothing.
- A rule singles out one item only if exactly one item passes ("is even" passes three of 4, 6, 8, 9).
- A rule with a fuzzy word ("big", "suspicious") cannot be tested by a stranger yet. Sharpen the word first.

## Go further

Use the notebook at `notebooks/01-you-already-do-mathematics.ipynb` in this repository. It works through the odd-one-out rules, the moving boundary, the six message cards, and the four locations, with every substitution printed.
