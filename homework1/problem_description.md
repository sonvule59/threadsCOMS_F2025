# THREADS OF AMES – HOMEWORK 1

**Topics:** Variables, Data Types, Input/Output, Functions, If/Else, For & While Loops  

## Instructions
- Match the **exact output format** shown for each problem.
- Only write inside the `# >>> WRITE YOUR CODE HERE` … `# <<< END WRITE` blocks.
- Read input from standard input using `input()` unless otherwise stated.

---

## Problem 1 — Rectangle Math
**Skills:** Variables, arithmetic, I/O  
**Goal:** Read `width` and `height` from **one** line. Print:
```
Area: <area>
Perimeter: <perimeter>
```
**Example**
```
Input:  5 3
Output:
Area: 15
Perimeter: 16
```

---

## Problem 2 — Celsius → Fahrenheit
**Skills:** Arithmetic, rounding, formatted output  
**Goal:** Read `C` and compute `F = C * 9/5 + 32`. Print with **one decimal place**:
```
Fahrenheit: <F>
```
**Example**
```
Input:  36.6
Output: Fahrenheit: 97.9
```

---

## Problem 3 — Even Helper
**Skills:** Functions, if/else  
**Goal:** Implement `p3_is_even(n: int) -> bool`. Read an integer and print `Even` or `Odd`.

**Example**
```
Input:  42
Output: Even
```

---

## Problem 4 — Grader
**Skills:** If/elif/else decision chains  
**Goal:** Read `score` (0–100) and print a letter:
- `A` for `90–100`
- `B` for `80–89`
- `C` for `70–79`
- `D` for `60–69`
- `F` for `<60`

**Example**
```
Input:  88
Output: B
```

---

## Problem 5 — Count Vowels
**Skills:** For loop, strings, sets  
**Goal:** Read a line of text. Count vowels `a e i o u` (both cases). Print:
```
Vowels: <count>
```
**Example**
```
Input:  Hello World
Output: Vowels: 3
```

---

## Problem 6 — Tiny Calculator
**Skills:** While loop, parsing, functions, error handling  
**Goal:** Repeatedly read commands `<op> <a> <b>` where `<op>` ∈ `{add, sub, mul, div}`.  
Print the result each time. End when the line is exactly `quit`.  
For invalid input or division by zero, print `Error`.

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

## Problem 7 — Prime Explorer
**Skills:** Functions, loops, basic algorithms  
**Goal:** Implement `p7_is_prime(n)`. Read `n (≥2)` and print all primes from `2..n` on **one line**, space-separated.

**Example**
```
Input:  10
Output: 2 3 5 7
```

---

## Problem 8 — Word Frequency
**Skills:** Strings, normalization, dictionaries, loops  
**Goal:** Read one line. Count words case-insensitively, ignoring leading/trailing punctuation `.,;:!?` and quotes.  
Print `word:count` **one per line**, sorted by word.

**Example**
```
Input:  "Hello, hello! And the world; the THE."
Output:
and:1
hello:2
the:3
world:1
```

---

## Problem 9 — GCD & LCM
**Skills:** While loop, functions, number theory  
**Goal:** Implement Euclid’s algorithm `p9_gcd(a,b)`. Then compute `p9_lcm(a,b) = abs(a*b)//gcd(a,b)` (return `0` if either is `0`).  
Print:
```
GCD: <g> LCM: <l>
```
**Example**
```
Input:  12 18
Output: GCD: 6 LCM: 36
```

---

## Problem 10 — FizzBuzz++
**Skills:** Condition combination, loops  
**Goal:** For integers `a..b` inclusive:
- multiple of 3 → `Fizz`
- multiple of 5 → `Buzz`
- multiple of 7 → `Bazz`  
Combine when multiple conditions apply (e.g., 15 → `FizzBuzz`, 21 → `FizzBazz`).  
Print **one token per line**.

**Example**
```
Input:  14 16
Output:
Bazz
FizzBuzz
16
```

---

### General Notes
- Keep outputs exactly as shown (spacing, capitalization, punctuation).
- Only add special formatting when asked (e.g., one decimal in Problem 2).
- Use clear variable names and keep logic inside the provided helper functions where applicable.
