---
name: mc-04-patterns-are-the-point
description: Teaches how to decide whether two drawings show the same pattern by naming the change, naming what counts as the same, and checking every feature that standard needs (pairings of networks, invariants, symmetry). Use when a learner asks whether two things are really the same, what an invariant is, or the difference between invariant and symmetry.
---

# Chapter 4: Patterns Are the Point

*Math Class Didn't Show Its Work* by Jason Karpeles

## The core idea

Name the change. Name what counts as the same. Then check every feature that standard needs. Two drawings that look different may show the same connections. Something that survives a change (an invariant) is not automatically a symmetry of the whole object. Always ask for three items: the object, the allowed change, and the standard for unchanged.

## Key equations (as the chapter writes them)

- Square links: A-B, A-C, B-D, C-D. Diamond links: P-Q, P-R, Q-S, R-S.
- A carried link: A-C becomes P-S under C → S.
- A row and its reflection: black | white | white becomes white | white | black.

An arrow such as A → P pairs a point with its partner. Carrying a link means replacing both endpoints with their partners.

## Coaching method

1. **Ask for their numbers.** Start with the learner's own example, or offer one from the book. Never hand over a finished answer first.
2. **Have them predict.** Before any calculation, ask: "What do you expect will happen?" A wrong guess is useful information, not a failure.
3. **Walk one substitution at a time.** Write the equation, replace one symbol with its number, say the result, then move to the next. Do not skip lines, and do not narrate a result without showing the step that produced it.
4. **Check with a reverse step.** Finish by working backward, or by a second route, and see whether it lands on the same place.
5. **Name where it stops working.** Every idea in this chapter has a boundary. Say it out loud so the learner knows when to trust the idea.

## Common sticking points

- **"They look different, so they are different."** Shape and pose are not the question. Ask for a pairing and carry each link through it.
- **"The counts agree, so it must work."** Matching counts are a necessary check, never a sufficient one. A specific pairing can still fail.
- **"One failed link means the networks differ."** No. It means this pairing fails. Another pairing may work.
- **Invariant versus symmetry.** The black count surviving a reflection is one invariant. A symmetry needs the stated standard to hold, and for the full filled arrangement that means every position matches its mirror position.
- **Left and right flipping.** Left means left on the page. Have them write the reversed row out cell by cell.

## Worked example with the book's numbers

Pairing: A → P, B → Q, C → S, D → R.

1. A-B becomes P-Q. Listed. Score 1.
2. A-C becomes P-S. Not listed. Score 0.
3. B-D becomes Q-R. Not listed. Score 0.
4. C-D becomes R-S. Listed. Score 1.
5. Total: $1 + 0 + 0 + 1 = 2$ of 4. One failed link already refutes "every link is preserved."

Repair by exchanging where C and D go: C → R, D → S. Then A-C becomes P-R, C-D becomes R-S, and all four land: $1 + 1 + 1 + 1 = 4$ of 4.

Now the row black-white-white reflected: it becomes white-white-black.
1. Black cells: 1 before, 1 after, $1 - 1 = 0$. Invariant.
2. Full arrangement: positions that match are $0 + 1 + 0 = 1$ of 3. Not a symmetry.
3. For white-black-white: $1 + 1 + 1 = 3$ of 3. A symmetry.

Reverse step: reflect the reflected row and confirm you return to the original.

## When the idea stops working

- Simple networks only: no repeated links and no link from a point to itself. If line length or direction carried meaning, links alone would not be enough.
- One failed link rules out only the pairing being tested. Ruling out every pairing takes many checks.
- A three-cell row and a left-right reflection only.

## Go further

Use the notebook at `notebooks/04-patterns-are-the-point.ipynb` in this repository. It carries every link through four pairings and compares the reflection under three standards, with each count printed.
