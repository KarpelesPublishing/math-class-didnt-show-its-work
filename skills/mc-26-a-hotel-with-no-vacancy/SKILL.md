---
name: mc-26-a-hotel-with-no-vacancy
description: Teaches how an infinite list can always make room (shift rules n to n + 1, n to n + k, evens and odds) and why 0.999... equals 1 (Chapter 26, A Hotel With No Vacancy). Use when a learner asks how infinity can be full yet have room, whether infinity is a number, how to merge two endless lists, or why 0.999... is not just less than 1.
---

# Chapter 26: A Hotel With No Vacancy

From *Math Class Didn't Show Its Work* by Jason Karpeles.

## The core idea

A full hotel can still make room, provided its rooms are labels rather than walls. Rooms 1, 2, 3, ... never end, so there is no last guest to push off the edge. A rule is checked two ways: do two guests ever land in the same room, and does every room get accounted for? The same patience with "never ending" explains why 0.999... names exactly the number 1.

## Key equations

- One new guest: $n \to n + 1$. No collision because $a + 1 = b + 1$ forces $a = b$.
- $k$ new guests: $n \to n + k$, leaving rooms 1 through $k$ free; $a + k = b + k$.
- A second endless list: old guest $n$ goes to $2n$, new guest $m$ goes to $2m - 1$. Working backward, room $r$ holds old guest $r/2$ if even, new guest $(r+1)/2$ if odd.
- Truncations: the number with $n$ nines is $1 - 10^{-n}$, and $0.999\ldots = 1$.

## How to coach it

1. **Ask for their own numbers.** "Pick a room number, say 40. Pick a number of new guests." Keep their choice for every step.
2. **Have them predict first.** "Before we move anyone: do you think one more guest can fit?" Let them argue "no". Then test.
3. **Walk one substitution at a time.** Guest in room 5 moves to $5 + 1 = 6$. Guest in room 6 moves to $6 + 1 = 7$. Then ask: who is in room 1 now?
4. **Check with a reverse step.** Pick any room and work backward: room 40 came from $40 - 1 = 39$. Then go forward to confirm: $39 + 1 = 40$.

## Common sticking points

- **"But the hotel is full."** Full means no empty room right now. It does not mean a last room exists. Ask: which guest is last? There is none, so nobody is pushed out.
- **"Infinity is a really big number."** It is not a number you can reach. The picture only ever shows the first few rooms; the rule is what reaches the rest.
- **Both lists to room $2n$.** Show room 2: old guest 1 and new guest 1 both land there, and odd rooms stay empty. The repair is $2m - 1$.
- **"0.999... is just below 1."** Every finite truncation is below 1, true. But the gap $10^{-n}$ shrinks tenfold with each nine, and any positive gap you name is beaten. No positive gap survives, so the endless string names 1.

## Worked example with the book's numbers

1. One guest: guest $n$ goes to room $n + 1$. Room 40 holds the guest from $40 - 1 = 39$. Check: $39 + 1 = 40$. Room 1 holds the new guest, since $n + 1 = 1$ needs $n = 0$, and there is no guest 0.
2. Four new guests: old guest 3 goes to $3 + 4 = 7$. Rooms 1 through 4 are free. Room 12 holds old guest $12 - 4 = 8$.
3. Second endless list: who is in room 31? It is odd, so new guest $(31 + 1)/2 = 16$. Check: $2 \times 16 - 1 = 31$. For room 17: $(17 + 1)/2 = 9$, check $2 \times 9 - 1 = 17$.
4. Nines: with 3 nines, $1 - 0.999 = 0.001$, below a requested gap of 0.01. With 5 nines the gap is 0.00001, below 0.0001.

## When the idea stops working

- A hotel that ends (say at room 6) cannot take the new guest: guest 6 would need room 7, which does not exist. Any real device with a fixed number of slots has a last room.
- The $n + k$ shift needs $k$ stated first; no single shift handles every possible $k$.
- Merging two lists needs both to be countable. A plan sending both to the same class of numbers collides.
- Only finite stages are ever drawn. An infinite decimal names the limit of its truncations; reading it as a list that stops somewhere misreads the notation.

## Practice to offer

- Under $n \to n + 1$, who is in room 40? (guest 39)
- If $k = 4$, which rooms are free and where does guest 3 go? (rooms 1 to 4; room 7)
- In the even and odd plan, who is in room 31? (new guest 16)
- How many nines make the gap from 1 below 0.0001? (five)

## Notebook

For a guided walk with pictures, open `notebooks/26-a-hotel-with-no-vacancy.ipynb` in this repository.
