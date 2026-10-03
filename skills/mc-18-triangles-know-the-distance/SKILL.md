---
name: mc-18-triangles-know-the-distance
description: Coaches the Pythagorean relationship (a² + b² = c²), the quick size check for a hypotenuse, why the squares add, bracketing a square root that is not whole, and spotting triangles that are not right (Chapter 18, Triangles Know the Distance of "Math Class Didn't Show Its Work"). Use when a learner asks how to find a diagonal, why legs are squared, how to estimate a square root by hand, or whether a triangle is a right triangle.
---

# Chapter 18: Triangles Know the Distance

*Math Class Didn't Show Its Work* by Jason Karpeles. Chapter idea: find the right angle first, then let the squares of the legs tell you the diagonal.

## The core idea in plain words

- In a right triangle the two legs meet at the right angle. The hypotenuse is the slanted side across from it.
- Square each leg, add, and the hypotenuse is the length whose square matches that sum.
- Quick check: the hypotenuse must be longer than the longer leg and shorter than the walk around the corner (the sum of the legs).
- The rule is earned, not handed down: count one big square's area two ways and the squares of the legs appear.
- When the square root is not whole, trap it between two numbers you can square, then shrink the trap.
- If the right angle is missing, the rule does not apply.

## Key equations (as the chapter writes them)

- a² + b² = c²
- max(a, b) < c < a + b
- (a + b)² = 4(ab/2) + c² = 2ab + c²
- c² = 2² + 4² = 20 and 4.47² = 19.9809
- 4² + 5² = 16 + 25 = 41, while 6² = 36

## Coaching method

1. Ask where their triangle comes from (a ladder, a screen, a ramp, a diagonal brace) and how they know there is a right angle.
2. Have them predict: "Is the diagonal longer or shorter than the longest side? Shorter than the two sides added?"
3. Walk each substitution: "3² + 4² = 9 + 16 = 25, and 5 x 5 = 25, so c = 5." Write every line.
4. Check by squaring the answer back, and by the quick check 4 < 5 < 7.
5. For square roots, square nearby numbers aloud until one lands below and the next lands above.

## Common sticking points

- "Why not just add the legs?" That is the walk around the corner, always longer than the diagonal. Show 3 + 4 = 7 versus 5.
- "Why squares?" Use the four-triangle picture: (3 + 4)² = 49, four triangles use 24, and 49 - 24 = 25 is what is left.
- "My calculator says 4.47, but 4.47 squared is not 20." Right: 4.47² = 19.9809. The decimal is a rounded display; the exact length is sqrt(20).
- "It looks like a right angle." A drawing that only looks square is not enough; the right angle must be stated or marked.

## Worked example with the book's numbers

Legs 3 and 4:
- 3² + 4² = 9 + 16 = 25.
- 5 x 5 = 25, so c = 5.
- Quick check: 4 < 5 < 3 + 4 = 7. Passes.

Legs 2 m and 4 m, a root that is not whole:
- c² = 2² + 4² = 4 + 16 = 20, so c = sqrt(20) m exactly.
- Whole numbers: 4 x 4 = 16 is below 20, 5 x 5 = 25 is above, so 4 < sqrt(20) < 5.
- Tenths: 4.4 x 4.4 = 19.36 is below, 4.5 x 4.5 = 20.25 is above, so 4.4 < sqrt(20) < 4.5.
- Nearest hundredth: about 4.47 m. Squared back: 4.47 x 4.47 = 19.9809, close to 20 but not equal.

Sides 4, 5, 6, is it a right triangle?
- 4² + 5² = 16 + 25 = 41 and 6² = 36.
- 41 is not 36, so it is not right. The third side stays 6; it is never replaced by sqrt(41).

## When the idea stops working

- It needs a flat surface and a stated right angle.
- Equal squares (like 3, 4, 5) do not by themselves prove a right angle in this chapter; the right angle must be supplied.
- A decimal answer is a rounded display, so squaring it back gives a number close to, not exactly, the target.

## Practice to offer

- Legs 5 and 12 (c = 13, and 12 < 13 < 17).
- Legs 5 and 5 in the four-triangle square: big 100, triangles 50, middle 50.
- Legs 1 and 3: sqrt(10) lies between 3.1 and 3.2.
- Sides 6, 7, 9: 36 + 49 = 85 versus 81, not right.

## Companion notebook

The notebook for this chapter is `notebooks/18-triangles-know-the-distance.ipynb` in this repository. It carries each calculation above with its substitution chain and a picture for each idea.
