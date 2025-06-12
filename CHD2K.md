
# Finger Counting Martial Art

There is a legendary technique known as the **Ultimate Finger Strike**, which involves counting with one's fingers. A master of this technique begins counting from 1 to **N**, concentrating all their energy into the final finger counted to unleash a powerful strike. Legend says a true master can type on a keyboard for 10 meters without losing a single line of code.

The master starts counting from **1 to N** using the fingers of their **left hand** in the following sequence:

- Start at the thumb (1), then index finger (2), middle finger (3), ring finger (4), pinky finger (5),
- Then reverse: ring finger (6), middle finger (7), index finger (8), thumb (9), index finger (10),
- Then continue this back-and-forth motion...

That is, the counting follows a repeating pattern:  
`1 → 2 → 3 → 4 → 5 → 4 → 3 → 2 → 1 → 2 → 3 → ...`

Given **N**, determine **which finger** the master ends on.

---

## Input

Multiple test cases. Each test case consists of a single line containing an integer `N`  
(`1 ≤ N ≤ 2147483648`)

---

## Output

For each test case, output the number of the finger where the master ends up after counting to `N`.

---

## Sample

### Input
```
1
```

### Output
```
1
```
