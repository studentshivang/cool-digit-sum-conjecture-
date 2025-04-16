# cool-digit-sum-conjecture-
Something I used to wonder as a kid, but chatgpt helped me almost prove it.




# Cool Digit Sum Conjecture

**Created by Shivang Dwivedi**

This is a fun and interesting math activity based on a pattern discovered while playing with numbers across different number systems (bases). We call it the **Cool Digit Sum Conjecture**.

> **Note:** This is not a formal mathematical theorem — just a cool pattern that Shivang noticed and explored for fun!

---

## What Is It?

The idea is simple:

> If you add two numbers, then find the **digital root** of the result, it often matches the digital root of all their digits added together.

Sounds confusing? Let’s break it down step by step.

---

## Step-by-Step Process (in Base 10):

1. Pick two numbers: let's say **22** and **33**
2. Add them: 22 + 33 = **55**
3. Add the digits of the result: 5 + 5 = **10**, and then 1 + 0 = **1**
   - This is called the **digital root**
4. Now add all the digits of the original numbers:
   - 2 + 2 + 3 + 3 = **10** → 1 + 0 = **1**

Both ways, we get the same final result: **1**

**Pattern matched!**

---

## Why Is It Cool?

This pattern seems to hold for many numbers, even in different number bases (like binary, octal, or hexadecimal). It connects number operations with the structure of the numbers themselves.

---

## More Examples

### Example 1 (Base 10)

- Numbers: 14 and 32
- Sum: 14 + 32 = 46 → 4 + 6 = **10** → 1 + 0 = **1**
- Digits: 1 + 4 + 3 + 2 = **10** → 1 + 0 = **1**
- **Match? Yes**

---

### Example 2 (Base 10)

- Numbers: 29 and 54
- Sum: 83 → 8 + 3 = **11** → 1 + 1 = **2**
- Digits: 2 + 9 + 5 + 4 = 20 → 2 + 0 = **2**
- **Match? Yes**

---

### Example 3 (Base 16 - Hexadecimal)

Hex uses A=10, B=11, ..., F=15

- A (10) + 5 = F (15)
- F → 15 → 1 + 5 = **6**
- Digits: A = 10, 5 = 5 → 10 + 5 = 15 → 1 + 5 = **6**
- **Match? Yes**

---

### Example 4 (Base 8)

- Numbers: 7 and 1
- 7 (base 8) + 1 (base 8) = 10 (base 8)
- Digits of 10 = 1 and 0 → 1 + 0 = **1**
- Digits of 7 and 1: 7 + 1 = **8** → 8 = 1 + 0 = **1**
- **Match? Yes**

---

## What Is a Digital Root?

A **digital root** is what you get when you keep adding the digits of a number until you’re left with a single digit.

### Examples:
- 123 → 1 + 2 + 3 = 6 → **6**
- 89 → 8 + 9 = 17 → 1 + 7 = **8**
- 999 → 9 + 9 + 9 = 27 → 2 + 7 = 9

---

## When Does It Work?

- It works most reliably when you follow the base rules correctly.
- Use digits that make sense in that base (e.g., avoid “9” in base 8).
- It's more of a **recreational pattern** than a strict rule.

---

## Features of This App

- Enter any two numbers and choose a base (2–36)
- See step-by-step breakdown
- Compare digital roots
- Dark, sleek interface inspired by **Solo Leveling**
- Works on mobile and desktop

---

## Live Demo

*Coming soon…*

---

## How to Use

1. Open `index.html` in your browser
2. Enter two numbers (e.g., `22` and `33`)
3. Choose a base (default is 10)
4. Click **Check Pattern**
5. Enjoy the breakdown!

---

## This Is Just for Fun

This whole project is for fun and curiosity. There’s no known proof or official paper — it’s a pattern discovered and explored for the love of numbers.

---

## License

**MIT License**

That means:
- You can use or modify the code freely
- You must keep my name (Shivang Dwivedi) as the original creator
- I’m not responsible for how it’s used

---

## Credits

- Pattern and idea by **Shivang Dwivedi**
- Built using HTML, CSS, and JavaScript

---

**Explore. Play. Question. That’s how math gets fun.**
