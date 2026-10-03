---
name: mc-19-why-circles-keep-saying-pi
description: Coaches why pi is the same for every circle, how to recover a radius from a circumference, how circumference and area scale differently, and how radians measure an angle by its arc (Chapter 19, Why Circles Keep Saying Pi of "Math Class Didn't Show Its Work"). Use when a learner asks what pi really is, mixes up radius and diameter, asks why doubling a radius quadruples the area, or asks what a radian is.
---

# Chapter 19: Why Circles Keep Saying Pi

*Math Class Didn't Show Its Work* by Jason Karpeles. Chapter idea: every ideal circle answers the same question, how many diameters fit around the boundary?

## The core idea in plain words

- Pi is not a mystery number. It is the answer to one question: lay the diameter along the edge of any circle, and a little more than three of them fit. That count is pi, about 3.14159.
- Keep answers exact as multiples of pi (like 1.2π or 49π). A decimal is a rounded display.
- Find the radius first. Many slips come from putting a diameter where the radius belongs.
- Lengths scale by one factor; areas scale by two, because the radius gets multiplied by itself.
- A radian measures an angle by the arc it reaches, counted in radii: s = rθ.

## Key equations (as the chapter writes them)

- π = C/d and C = πd
- 2πr = 14π, then π(7)² = 49π
- A = πr²
- s = rθ and θ = s/r

## Coaching method

1. Ask for a real circle: a pizza, a table, a wheel, a pipe. Get which length they know (diameter, radius, circumference).
2. Have them predict: "If I double the radius, does the area double?"
3. Walk it one substitution at a time. Always say which length you hold before writing a formula: "I have the circumference, so first r."
4. Check by reverse: put the radius back into 2πr and see if the circumference returns.
5. Ask them to say what the unit is (centimeters or square centimeters).

## Common sticking points

- Radius versus diameter: radius is center to edge; diameter is edge to edge through the center, twice as long.
- "Why is the ratio only pi for the diameter?" A chord that misses the center is shorter than the diameter; C divided by a 0.8-diameter chord is about 3.93, not pi.
- "Why does area grow faster than circumference?" Circumference is a length, area is a length times a length. Doubling r doubles C but quadruples A.
- "Why radians?" Because s = rθ then needs no conversion factor. Degrees are a fraction of a turn: 120/360 is a third.

## Worked example with the book's numbers

Tabletop, diameter 1.2 m:
- C = π x 1.2 = 1.2π m, which is 3.77 m to the nearest hundredth.
- C / d = 1.2π / 1.2 = π.

Recover the radius, circumference 14π cm:
- 2πr = 14π, so r = 14π / 2π = 7 cm.
- Area = π x 7² = 49π cm².
- Check: 2π x 7 = 14π.
- The slip: π x 14² = 196π, and 196 / 49 = 4, four times too big.

Doubling the tabletop radius (0.6 m to 1.2 m):
- Circumference 2π x 1.2 = 2.4π m, which is 2 times 1.2π.
- Area π x 1.2² = 1.44π m², which is 2² = 4 times 0.36π.

Arc for 120 degrees on radius 3:
- 120/360 = 1/3 of a turn, so θ = 1/3 x 2π = 2π/3 radians.
- s = rθ = 3 x 2π/3 = 2π.
- Check: 1/3 x 6π = 2π.

## When the idea stops working

- Everything here describes an ideal circle with a declared radius. A real wheel or ring has thickness and wobble.
- s = rθ needs θ in radians.
- Circumference (meters) and area (square meters) cannot be compared directly, only their growth factors can.

## Practice to offer

- Diameter 10: C = 10π, C/d = π.
- Circumference 20π cm: r = 10 cm, area 100π cm².
- Radius 6, angle 60 degrees: θ = π/3, s = 2π.
- Radius times 5: circumference by 5, area by 25.

## Companion notebook

The notebook for this chapter is `notebooks/19-why-circles-keep-saying-pi.ipynb` in this repository. It shows each calculation with its substitution chain and a picture for each idea.
