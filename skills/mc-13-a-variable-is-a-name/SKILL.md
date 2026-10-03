---
name: mc-13-a-variable-is-a-name
description: Teaches variables as names, expressions as instructions, combining like terms, and expanding products with every cross-product. Use when a learner asks why 3(n + 2) and 3n + 2 differ, which terms can be combined, why (x + 2)(x + 5) is not x squared plus 10, or how a fixed fee plus a rate becomes a rule.
---

# Chapter 13: A Variable Is a Name

## The core idea

A letter is a name that saves a place for any value the context allows. An expression is an instruction, and the grouping tells you what to do and in what order. Only like terms (same variable part) can be combined. Multiplying two sums means every piece of one meets every piece of the other, so nothing is dropped. In a rule such as "a fixed fee plus a rate per item", one part stays put and one part moves with the count.

## Key equations (as the chapter writes them)

- 3(n + 2) and 3n + 2, at n = 4: 18 and 14
- 4x + 3 - 2x + 5 = 2x + 8, because 4x - 2x = (4 - 2)x
- (x + 2)(x + 5) = x^2 + 7x + 10
- C(n) = $4 + ($1.50/item) n, so C(6) = $4 + $9 = $13

## Coaching method

1. Ask for the learner's own rule or expression (a price, a tip, a phone plan) and an input they like.
2. Predict first: "If we change the grouping, will the answer move? By how much?"
3. Walk one substitution at a time: replace the letter with the number, then do one operation per line, keeping parentheses around negatives.
4. Check with a reverse step or a second input: simplify, then test old and new forms at one or two values. A mismatch proves an error; a match is a check, not a proof.
5. Have the learner read the symbols back in words ("add 2, then triple") before moving on.

## Common sticking points

- Parentheses ignored: 3(n + 2) read as 3n + 2. Say "three copies of the whole group".
- Combining unlike terms (2x + 3x^2 = 5x). Use strips and squares: different shapes do not merge.
- Trusting one lucky input. At x = 0, 2x + 3x^2 and 5x both give 0, so the error hides. Always try a second value.
- Multiplying two sums and keeping only the corner pieces. Draw the four regions of the rectangle.
- Thinking C(n) means C times n. C is the name of the rule.

## Worked example with the book's numbers

Add two then triple, at n = 4:
1. Grouped: n + 2 = 4 + 2 = 6, then 3 x 6 = 18.
2. Ungrouped: 3 x 4 = 12, then 12 + 2 = 14.
3. Gap: 18 - 14 = 4, the two missing copies of 2 (at n = 1: 9 - 5 = 4 too).

Four regions at x = 1: width x + 5 = 6, height x + 2 = 3, area 3 x 6 = 18. Regions: 1 + 5 + 2 + 10 = 18. The shortcut x^2 + 10 = 1 + 10 = 11 misses 5x + 2x = 5 + 2 = 7, and 11 + 7 = 18.

Cost rule at n = 6: 4 + 1.50 x 6 = 4 + 9 = 13. Reverse: C(6) - C(2) = 13 - 7 = 6 = 1.50 x 4.

## When the idea stops working

- Combining works only for like terms; 2x + 3x^2 stays as it is (at x = 3 it is 33, while 5x is 15).
- The rectangle picture needs positive lengths; distribution itself holds for any number.
- The cost rule is an invented example, and n = -3 is outside the model even though the arithmetic runs (4 - 4.50 = -0.50).

## Companion notebook

See the four demonstrations with pictures in `notebooks/13-a-variable-is-a-name.ipynb` in this repository.
