# Introduction to Programming & Python — Presentation Web App

A clean, modern, distraction-free presentation web app designed for lectures introducing programming fundamentals and Python.

---

## 🚀 How to Run

### Method 1: Direct File Open (Easiest)
Simply double-click `index.html` or open it in any modern browser (Google Chrome, Microsoft Edge, Brave, Firefox, Safari).

### Method 2: Local HTTP Server (Recommended)
Open a terminal in this folder and run:
```bash
python -m http.server 8000
```
Then navigate to: `http://localhost:8000` in your web browser.

---

## 📓 Google Colab Practice Notebook

A comprehensive companion workbook with **63 cells** across 6 modules is available in this repository:
- **File:** [`python_foundations_practice.ipynb`](file:///d:/Usizo%20Lecture/python_foundations_practice.ipynb)
- **Features:**
  - Inductive learning design: *Observe & Predict $\rightarrow$ Experiment $\rightarrow$ Solve $\rightarrow$ Self-Check*.
  - Covers all 22 slide topics: `print()` formatting, escape sequences, variables, data types, tokens, all 7 operator families, expressions vs. statements, PEMDAS precedence, and type casting.
  - Interactive challenges with `# TODO` prompts, automated `assert` tests, and collapsible hints & solutions.
  - **Capstone Challenge:** *"The Usizo Smart Chai Counter POS"* bill calculator and receipt generator.
- **How to Open in Colab:**
  1. Open [Google Colab](https://colab.research.google.com/).
  2. Click **File** $\rightarrow$ **Upload notebook**.
  3. Select `python_foundations_practice.ipynb` from this folder.

---

## ⌨️ Presentation Keyboard Shortcuts

| Key | Action |
| :--- | :--- |
| <kbd>→</kbd> / <kbd>Space</kbd> / <kbd>PageDown</kbd> | **Next Slide** |
| <kbd>←</kbd> / <kbd>PageUp</kbd> | **Previous Slide** |
| <kbd>Home</kbd> / <kbd>End</kbd> | **First / Last Slide** |
| <kbd>N</kbd> | **Toggle Speaker Notes / Teleprompter** |
| <kbd>G</kbd> | **Toggle Slide Grid Overview** (Jump directly to any of the 22 slides) |
| <kbd>F</kbd> | **Toggle Fullscreen Presentation Mode** |
| <kbd>Esc</kbd> | Close Modals |

---

## 📚 Complete 22-Slide Outline (Original Content in Logical Order)

1. **Slide 1: What is a Program?**
   - Human Language is Recipe-Based (Tea-making procedure analogy).
   - A Program is Just a Recipe (Unambiguous step-by-step instructions).
   - Strict Order Matters.
   - *Visual:* 4-step Tea-Making Procedure diagram.

2. **Slide 2: The Problem: Computers Can't Understand Human Words**
   - Human Language Has Ambiguity.
   - Silicon Only Knows Electricity (0 = OFF, 1 = ON).
   - The Early Era (Punch cards and manual switches).
   - *Visual:* Human English vs. Machine Binary divide card.

3. **Slide 3: High-Level Programming Languages**
   - Designed for Humans (`print`, `if`, `while`).
   - 100x Productivity.
   - Portability Across Devices.
   - *Visual:* 14 lines of cryptic Assembly vs. 1 line of Python.

4. **Slide 4: Compilers vs. Interpreters**
   - The Need for a Translator.
   - Compiler (Like a Published Book — C, C++, Rust).
   - Interpreter (Like a Live Spoken Translator — Python).
   - *Visual:* Dual workflow comparison flowchart.

5. **Slide 5: Welcome to Python**
   - Origins (1991, Guido van Rossum, Monty Python).
   - Readability First (Clean indentation, no curly braces).
   - Gentle Yet Mighty (Beginners to AI/NASA).
   - *Visual:* Python at a glance & Zen of Python highlight.

6. **Slide 6: The `print()` Statement: Giving Code a Voice**
   - Speaking to the Screen (Standard Output).
   - Multiple Items (Commas for automatic spaces).
   - Escape Sequences (`\n` for new line, `\t` for tab, `\"` for quotes).
   - **Code Comments (`#`):** Notes for humans that Python ignores. *Mistakes & red errors are a normal part of coding!*
   - *Visual:* Code & Terminal output previewer + modern f-strings.

7. **Slide 7: Variables: The Labeled Storage Containers**
   - The Kitchen Jars Analogy (Salt, Sugar, Pepper).
   - Memory with a Name Tag.
   - The Assignment Operator (`=`).
   - Values Can Be Replaced.
   - *Visual:* Labeled memory boxes (`salt`, `sugar_spoons`, `pepper`).

8. **Slide 8: Rules for Naming Variables in Python**
   - Allowed Characters Only (`a-z`, `0-9`, `_`).
   - Cannot Start with a Number (`player1` ✅ vs `1player` ❌).
   - Case-Sensitive (`age`, `Age`, `AGE` are distinct).
   - No Python Keywords (`print`, `if`, `for`).
   - *Visual:* Quick reference Dos & Don'ts table + `snake_case` style convention.

9. **Slide 9: Data Types: What Kind of Stuff Goes Inside?**
   - Why Types Matter (Can't pour soup into an envelope).
   - The Fundamental Types (`str`, `int`, `float`/`double`).
   - Automatic Detection.
   - *Visual:* Crucial contrast: `5 + 5 = 10` (Math) vs. `"5" + "5" = "55"` (Text concatenation).

10. **Slide 10: Other Data Types: The Boolean (`bool`)**
    - Only Two States in the Universe (`True` or `False`).
    - Everyday Real-Life Switches (Light switch ON/OFF, Door locked/unlocked).
    - The Apps We Use Everyday (`is_user_logged_in`, `is_cart_empty`, `is_charging`).
    - *Visual:* 4-toggle real-life switchboard.

11. **Slide 11: The `input()` Statement: Listening to the User**
    - A Two-Way Conversation (Pauses and waits for Enter).
    - The Golden Rule: It's Always a String.
    - Converting to Numbers (Type Casting with `int()`).
    - *Visual:* Interactive dialogue flow in code.

12. **Slide 12: Python Tokens: The 5 Building Blocks**
    - What is a Token? (The smallest individual units of code).
    - The 5 Types: Keywords, Identifiers, Literals, Operators, Punctuators.
    - **Code Comments Note:** Notes for humans that Python skips. *Debugging errors is how real programmers learn!*
    - *Visual:* Complete mini-program with color-coded token badges and legend.

13. **Slide 13: Python Operators: The 7 Core Families**
    - Overview of the 7 operator types: Arithmetic, Comparison (Relational), Assignment, Logical, Bitwise, Membership, Identity.
    - *Visual:* 7-family matrix cards with symbols and definitions.

14. **Slide 14: Arithmetic Operators: Doing Math in Python**
    - Standard operations: `+`, `-`, `*`.
    - Division difference: True Division (`/` float) vs Floor Division (`//` integer).
    - Modulus (`%` remainder) & Exponentiation (`**` power).
    - *Visual:* Arithmetic cheat sheet table with even/odd check tip.

15. **Slide 15: Comparison Operators: Asking Yes/No Questions**
    - Comparison expressions always produce Booleans (`True` / `False`).
    - The classic beginner trap: `=` (Assignment) vs `==` (Equality check).
    - Relational set: `==`, `!=`, `>`, `<`, `>=`, `<=`.
    - *Visual:* Relational reference table with Boolean outputs and caution alert.

16. **Slide 16: Logical Operators: Combining Conditions**
    - Connecting multiple truths to make complex decisions.
    - The core trio: `and` (both must pass), `or` (at least one passes), `not` (inverts truth).
    - Real-life application logic: driver's license check, student discounts, account access.
    - *Visual:* Multi-condition evaluation cards with live Boolean badges.

17. **Slide 17: Assignment Operators: Storing & Updating Data**
    - Basic assignment `=` vs. compound/augmented assignments (`+=`, `-=`, `*=`, `/=`, `//=`, `%=`, `**=`).
    - Shorter, cleaner code that avoids repeating variable names.
    - *Visual:* Full compound assignment table with before/after trace for initial `x = 10`.

18. **Slide 18: Membership & Identity: Checking Presence & Object ID**
    - Membership (`in`, `not in`): tests membership in text and collections.
    - Identity (`is`, `is not`): tests whether two variables point to the exact same memory address in RAM.
    - Crucial contrast: `==` (Value Equality) vs. `is` (Object Identity).
    - *Visual:* Side-by-side sequence testing and RAM address identity comparison cards.

19. **Slide 19: Expressions: Producing Values in Code**
   - Core Definition: An expression is any code evaluated by Python to produce a value (even `None`).
   - The Assignment Test: Anything that can sit on the right-hand side of `=`.
   - Nested expressions: `(7 - 3) * 0.5`, `(7 - 3)`, `7`.
   - *Visual:* Right-hand side assignment formula card with evaluated examples.

20. **Slide 20: Anatomy of Expressions: Types & Building Blocks**
   - The 4 ingredients: Variables, Values, Operators, and Functions.
   - Expression (produces value) vs. Statement (executes an action).
   - 4 common expression types: Arithmetic, Logical, String, and Conditional (ternary).
   - *Visual:* 4 categorized code expression cards with results.

21. **Slide 21: Operator Precedence: The Order of Operations**
   - Execution hierarchy: Parentheses `()` > Exponents `**` > Math `* / // %` > Math `+ -` > Comparisons > Logical `not, and, or`.
   - The Golden Rule: *"When in doubt, use parentheses!"*
   - *Visual:* Step-by-step trace of `5 + 2 * 3 ** 2 - (4 / 2)` yielding `21.0`.

22. **Slide 22: Type Conversion: Changing Data Types**
   - Why conversion is necessary in strongly typed Python.
   - Implicit type conversion (automatic promotion, e.g., `5 + 2.5` → `7.5`).
   - Explicit type casting: `int()`, `float()`, `str()`, `bool()`.
   - *Visual:* Conversion cheat sheet table and `ValueError` common pitfall callout.
