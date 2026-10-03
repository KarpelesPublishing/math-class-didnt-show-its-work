---
name: mc-20-how-a-circle-becomes-a-wave
description: Coaches sine, cosine and tangent as ratios fixed by the angle, the unit circle at the quarter turns, how a turning point unrolls into a sine or cosine wave, and the height model with midline and amplitude (Chapter 20, How a Circle Becomes a Wave of "Math Class Didn't Show Its Work"). Use when a learner asks what sine and cosine really are, why tangent is undefined, why sine waves repeat, or how to read h = midline + amplitude x sin.
---

# Chapter 20: How a Circle Becomes a Wave

*Math Class Didn't Show Its Work* by Jason Karpeles. Chapter idea: sine and cosine start as ratios in a triangle, grow into coordinates on a circle, and unroll into a wave.

## The core idea in plain words

- In a right triangle, the angle decides the ratios. Make the triangle bigger or smaller and the sides change, but sine, cosine and tangent do not, because top and bottom change together.
- Sine is opposite over hypotenuse. Cosine is adjacent over hypotenuse. Tangent is opposite over adjacent, which equals sine divided by cosine.
- On the unit circle (radius 1, center at the origin) the point at angle θ is (cos θ, sin θ). Cosine is across, sine is up.
- Record just one coordinate as the point turns and you get a wave. After one full turn, 2π, the values repeat.
- In h = midline + amplitude x sin θ, the midline lifts the wave and the amplitude stretches it. Top is midline plus amplitude; bottom is midline minus amplitude.

## Key equations (as the chapter writes them)

- sin θ ÷ cos θ = 3/5 ÷ 4/5 = 3/4
- tan θ = sin θ / cos θ
- (cos θ, sin θ)
- (-1)² + 0² = 1
- Sine points: (π/2, 1); cosine values at the quarter turns: 1, 0, -1, 0, 1
- h(θ) = 2 m + (1.5 m) sin θ and 2 m - 1.5 m = 0.5 m

## Coaching method

1. Ask where they met sine or cosine (a ramp, a wheel, a sound, a tide). Use their setting when you can.
2. Have them predict: "If I shrink this triangle to one fifth, does the sine change?"
3. Walk every substitution: "sin = opposite / hypotenuse = 3/5." For the model: "h = 2 + 1.5 x (-1) = 0.5."
4. Check: Pythagorean check on the sides, radius check (cos)² + (sin)² = 1 on the circle, top and bottom bounds on the model.
5. Ask them to name which coordinate a wave-shaped graph is recording.

## Common sticking points

- "Which leg is opposite?" It faces the chosen angle; the adjacent leg touches it. The other acute angle swaps the two.
- "Why is tangent undefined at π/2?" The point is (0, 1), so tan = 1/0, and dividing by zero has no answer.
- "Why are there negatives?" The sign comes from where the point sits: left is negative across, below is negative up.
- "Sine is 0 at π too, so is π a period?" No. The full cycle needs 2π.
- "Is the wave a position?" No. Across the graph is the angle, not a place on the circle.

## Worked example with the book's numbers

The 3-4-5 triangle:
- sin = 3/5, cos = 4/5, tan = 3/4.
- Check: (3/5) / (4/5) = 3/4, the same as tangent.
- Shrink every side to 1/5: sin = (3/5)/1 = 3/5, unchanged. Check: (3/5)² + (4/5)² = 9/25 + 16/25 = 1 = 1².

The point at π/2:
- (cos, sin) = (0, 1).
- Radius check: (0)² + (1)² = 1.
- Tangent: 1/0 is undefined.

Unrolling sine over one full turn:
- Quarter-turn values: 0, 1, 0, -1, 0.
- Turn so far: 4/4 x 2π = 2π, back where it began.

Height model h = 2 m + (1.5 m) sin θ:
- Top: 2 + 1.5 = 3.5 m. Bottom: 2 - 1.5 = 0.5 m.
- Heights at 0, π/2, π, 3π/2, 2π: 2, 3.5, 2, 0.5, 2 m.
- At 3π/2: h = 2 + 1.5 x (-1) = 0.5 m.

## When the idea stops working

- The triangle ratios need a right triangle and an acute chosen angle, with all sides in the same unit.
- Angle conventions (start at the positive horizontal axis, turn counterclockwise, use radians) must stay fixed, or every label changes.
- The height model here is constructed: no time, speed or physical motion is supplied. With amplitude 0 it is a flat line with no least positive period.

## Practice to offer

- Legs 6 and 8, hypotenuse 10: sine opposite the 6 is 6/10 = 3/5.
- At 2π: cos = 1, sin = 0, because it reaches the same point as 0.
- sin(5π/2) = 1.
- Height at 3π/2: 2 + 1.5 x (-1) = 0.5 m.

## Companion notebook

The notebook for this chapter is `notebooks/20-how-a-circle-becomes-a-wave.ipynb` in this repository. It carries each calculation with its substitution chain and a picture for each idea.
