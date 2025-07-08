# 🔐 Python Password Generator

This is a beginner-friendly **Python-based password generator** that creates strong, randomized passwords using uppercase letters, lowercase letters, digits, and special characters. It’s a great way to demonstrate foundational Python skills like string manipulation, conditional logic, and loops.

---

## 🔧 Features

- Generates multiple strong passwords
- Customizable:
  - Password length
  - Number of passwords
  - Character types included (controlled via booleans)
- Uses the `random` module for character shuffling
- Clean, console-based output

---

## 💻 Technologies Used

- Python 3.x
- `random` module
- String concatenation and manipulation
- Boolean flags for conditional logic
- `for` loops
- `random.sample()` for character shuffling

---

## 📋 Code Behavior

```plaintext
✅ If a character type (uppercase, lowercase, digits, special) is set to True:
→ It will be included in the password pool.

🧠 The script:
- Builds a combined character pool based on True/False flags
- Randomly selects a set number of characters (e.g., 20) from the pool
- Loops to generate the desired number of passwords (e.g., 10)

🖥️ Console Output:
Each run produces 10 randomized 20-character passwords, like:
qL%#KViCZotxNRfAp@63
0ZYriAXj4LtC!WGQ8fv^
>ONvAYK3u@7itZqJ1*R%

