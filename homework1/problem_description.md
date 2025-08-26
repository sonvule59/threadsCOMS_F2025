# CS101 – Unit 1 Assignment

**Topics:** Variables, Data Types, Input/Output, Functions, If/Else, For & While Loops

**Instructions for students**

* Read the description for each problem carefully. Your program must match the **exact output format** shown.
* When coding in the starter file, write **only** inside the blocks marked `# >>> WRITE YOUR CODE HERE` … `# <<< END WRITE`.
* Unless stated otherwise, inputs are read from standard input using `input()`.

---

## Problem 1 — Rectangle Math

**Skills:** Variables, arithmetic, basic I/O
**Goal:** Read two numbers `width` and `height` from **one** line, compute **area** and **perimeter**, then print both on separate lines.

**Input**
Two numbers on one line: `width height` (may be integers or floats).

**Output**

```
Area: <area>
Perimeter: <perimeter>
```

* Print numeric values without unnecessary trailing zeros where possible (e.g., `15` rather than `15.0`).

**Example**

```
Input:  5 3
Output:
Area: 15
Perimeter: 16
```

---

## Problem 2 — Who Am I?

**Skills:** Data types, parsing, formatted output
**Goal:** Read `name` (string), `age` (int), and `height_m` (float) from **one** line, then print a formatted sentence.

**Input**
One line: `<name> <age> <height_m>`
Example: `Ava 19 1.67`

**Output**

```
<name> is <age> years old and <height_m>m tall.
```

**Example**

```
Input:  Ava 19 1.67
Output: Ava is 19 years old and 1.67m tall.
```

---

## Problem 3 — Celsius → Fahrenheit

**Skills:** Arithmetic, rounding, formatted output
**Goal:** Convert Celsius to Fahrenheit using `F = C * 9/5 + 32` and print with **one decimal place**.

**Input**
One float: `C`

**Output**

```
Fahrenheit: <F>
```

* `<F>` must be rounded to **one decimal place**.

**Example**

```
Input:  36.6
Output: Fahrenheit: 97.9
```

---

## Problem 4 — Even Helper

**Skills:** Functions, if/else
**Goal:** Implement `is_even(n: int) -> bool`. Then read an integer and print `Even` or `Odd` using your function.

**Input**
One integer: `n`

**Output**
`Even` **or** `Odd`

**Example**

```
Input:  42
Output: Even
```

---

## Problem 5 — Grader

**Skills:** If/elif/else decision chains
**Goal:** Read a score `0–100` and print a letter grade:

* `A` for `90–100`
* `B` for `80–89`
* `C` for `70–79`
* `D` for `60–69`
* `F` for `<60`

**Input**
One integer: `score`

**Output**
One of: `A`, `B`, `C`, `D`, `F`

**Example**

```
Input:  88
Output: B
```

---

## Problem 6 — Sum of Multiples

**Skills:** For loop, accumulation
**Goal:** Read `n`, and compute the sum of all integers `i` in `1..n` such that `i` is divisible by **3 or 5**.

**Input**
One integer: `n`

**Output**
A single integer: the sum.

**Example**

```
Input:  10
Output: 33
```

(Explanation: 3+5+6+9+10 = 33)

---

## Problem 7 — Collatz Steps

**Skills:** While loop, conditional logic
**Goal:** Given `n > 0`, repeatedly apply:

* if `n` is even: `n = n // 2`
* else: `n = 3*n + 1`
  Count **how many steps** it takes to reach `1`, and print that count.

**Input**
One integer: `n` (must be `> 0`)

**Output**
A single integer: number of steps to reach `1`.

**Example**

```
Input:  6
Output: 8
```

(Sequence: 6 → 3 → 10 → 5 → 16 → 8 → 4 → 2 → 1)

---

## Problem 8 — Count Vowels

**Skills:** For loop, strings, sets
**Goal:** Read a line of text and count vowels `a, e, i, o, u` (both uppercase and lowercase). Print the total.

**Input**
One line of text (may contain spaces).

**Output**

```
Vowels: <count>
```

**Example**

```
Input:  Hello World
Output: Vowels: 3
```

---

## Problem 9 — Leap Year Checker

**Skills:** Function + if/else with rule ordering
**Goal:** Implement `is_leap(year)` using rules:

1. If divisible by **400** → leap
2. Else if divisible by **100** → not leap
3. Else if divisible by **4** → leap
4. Else → not leap
   Then read `year` and print `Leap` or `Not Leap`.

**Input**
One integer: `year`

**Output**
`Leap` **or** `Not Leap`

**Examples**

```
Input:  2000
Output: Leap

Input:  1900
Output: Not Leap

Input:  2024
Output: Leap
```

---

## Problem 10 — Tiny Calculator

**Skills:** While loop, parsing, functions, error handling
**Goal:** Repeatedly read commands of the form `<op> <a> <b>` where `<op>` ∈ `{add, sub, mul, div}` and `a`, `b` are numbers. Print the result each time. End when the input line is exactly `quit`.

* On **division by zero** or **invalid input/op**, print `Error`.

**Input**
Multiple lines, each either:

* `add a b`
* `sub a b`
* `mul a b`
* `div a b`
* `quit` (to end)

**Output**
One line per command:

* the numeric result (for valid commands), or
* `Error` for invalid commands/operands or division by zero.

**Example session**

```
Input:
add 3 4
mul 1.5 2
div 10 0
quit

Output:
7.0
3.0
Error
```

---

## General Notes

* Follow the **exact output strings** shown (capitalization, spacing, punctuation). Autograders are strict.
* For numeric printing, only apply special formatting when explicitly asked (e.g., one decimal place in Problem 3). Otherwise, plain printing is fine.
* Readability matters: use clear variable names and keep logic inside helper functions when provided.
