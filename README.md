# session-13
A collection of basic Python practice exercises covering arithmetic operations, loops, conditionals, functions, and random number generation.
# 🐍 Basic Python Practice Collection

## 📖 Overview

This repository contains several basic Python practice programs.

The exercises are designed to help beginners understand:

- Variables
- Functions
- Loops
- Conditional statements
- Lists
- Random module
- Basic arithmetic operations

Each snippet demonstrates a different fundamental Python concept.

---

## 📂 Practice Programs Included

### 1️⃣ Word Counter (Pages × Words)

Calculates total words based on number of pages and words per page.

```python
pages = int(input("Number of pages: "))
word_per_page = int(input("Number of words per page: "))
total_word = pages * word_per_page
print(total_word)
```

---

### 2️⃣ Average Score Calculator

Calculates the average of a list of student scores.

```python
def hitung_rata_rata(nilai):
    total = 0
    for n in nilai:
        total += n
    rata2 = total / len(nilai)
    return rata2

nilai_siswa = [80, 90, 75, 95]
hasil = hitung_rata_rata(nilai_siswa)
print("Rata rata:", hasil)
```

---

### 3️⃣ Odd or Even Checker

Checks whether a number is odd or even.

```python
def odd_or_even(number):
    if number % 2 == 0:
        return "This is an even number."
    else:
        return "This is an odd number."
```

---

### 4️⃣ Loop Practice (Range 1–20)

Prints a message when the number reaches 20.

```python
def my_function():
    for i in range(1, 21):
        if i == 20:
            print("Kamu mendapatkan 20!")

my_function()
```

---

### 5️⃣ Dice Simulator

Simulates a random dice roll.

```python
from random import randint

dice = ["1", "2", "3", "4", "5", "6"]
dice_acak = randint(0, 5)
print(dice[dice_acak])
```

---

### 6️⃣ Generation Checker

Determines generation category based on birth year.

```python
tahun = int(input("Kamu lahir tahun berapa? "))

if tahun > 1980 and tahun < 1994:
    print("Kamu adalah Milenial!")
elif tahun >= 1994:
    print("Kamu adalah Gen Z!")
```

---

## 🧠 Concepts Practiced

- Input and Output
- Data types (int, list, string)
- Functions
- For loops
- Conditional logic (if-elif-else)
- Random number generation
- Arithmetic calculations

---

## 🛠 Requirements

- Python 3.x

---

## 🎯 Purpose

This repository is created for learning and practicing basic Python programming concepts.

---

## 👤 Author

Andrian Wijaya

---

## 📜 License

This project is created for educational purposes.
