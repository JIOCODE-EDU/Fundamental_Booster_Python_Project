# 🧾 Fundamental Booster — Interactive Personal Data Collector

An interactive Python console application that captures, processes, and displays personal information from the user using fundamental Python functions and concepts — `print()`, `input()`, variables, operators, type casting, and the built-in `type()` / `id()` functions.

---

## 📌 1. What is this Project?

**Fundamental Booster** is a beginner-level Python project built for the *PR-1* assignment (Red & White Skill Education — Python Data Science track).

It is a command-line application that:

- Collects a user's **name, age, height, and favourite number**
- Stores each value in a variable with an **appropriate data type**
- Performs simple **calculations and type conversions** on the collected data
- Displays a clean, formatted **summary** of everything it learned about the user

It's designed to reinforce the absolute fundamentals of Python before moving on to more advanced data science topics.

---

## 📌 2. Key Concepts Demonstrated

| Concept | Description |
|--------|-------------|
| **`input()`** | Gathers different types of personal information from the user |
| **`print()`** | Displays formatted messages and guides the user through each step |
| **Variables & data types** | Stores each piece of collected data with a suitable type (`str`, `int`, `float`) |
| **Operators** | Arithmetic operators (`+`, `-`, `*`, `/`) used for calculations like birth year |
| **String formatting** | f-strings / concatenation used to build user-friendly output |
| **Type casting** | Converts `input()` strings into `int`/`float` where needed |
| **`type()`** | Displays the data type of each variable |
| **`id()`** | Displays the memory address of each variable |

---

## 📌 3. Why Type Casting Matters Here

| Reason | Explanation |
|--------|-------------|
| **`input()` always returns a string** | Age, height, and favourite number must be explicitly cast |
| **Accurate calculations** | Birth year math requires `age` to be an `int`, not a `str` |
| **Clean output** | Casting float results (e.g. height-based calcs) keeps display readable |
| **Prevents runtime errors** | Avoids `TypeError` when mixing strings and numbers |

---

## 📌 4. Program Flow

### ➤ **Welcome Instructions**
- Display a welcome message and a brief description of what the program does.

### ➤ **Collect Information**
- Prompt the user to enter their **name** (`str`), **age** (`int`), **height** in meters (`float`), and **favourite number** (`int`).

### ➤ **Data Processing**
- Perform calculations with the user-provided data, such as estimating **birth year** from age.
- Determine the **type** and **memory address** of each variable.

### ➤ **Display Results**
- Print a summary of the user's information in a user-friendly way.
- Show messages explaining how data types were converted where applicable.

### ➤ **Exit Message**
- End with a thank-you message and encourage the user to keep exploring Python.

---

## 📌 5. Example Console Interaction

```text
Welcome to the Interactive Personal Data Collector!

Please enter your name: Alice
Please enter your age: 25
Please enter your height in meters: 1.68
Please enter your favourite number: 7

Thank you! Here is the information we collected:

Name: Alice (Type: <class 'str'>, Memory Address: 140703847239588)
Age: 25 (Type: <class 'int'>, Memory Address: 9793456)
Height: 1.68 (Type: <class 'float'>, Memory Address: 140703847253232)
Favourite Number: 7 (Type: <class 'int'>, Memory Address: 9793312)

Your birth year is approximately: 1998 (based on your age of 25)

Thank you for using the Personal Data Collector. Goodbye!
```

## 📌 6. Requirements Checklist

| Requirement | Covered |
|-------------|---------|
| Use of `input()` to gather personal information | ✅ |
| Use of `print()` for formatted guidance and output | ✅ |
| Store each value with an appropriate data type | ✅ |
| Use arithmetic operators for calculations (birth year) | ✅ |
| String concatenation / f-strings for friendly output | ✅ |
| Type casting from `str` to `int` / `float` | ✅ |
| Display `type()` for each variable | ✅ |
| Display `id()` (memory address) for each variable | ✅ |

---

## 📌 7. Assumptions Made

- Age is assumed to be a whole number (`int`), not a decimal.
- Height is collected in **meters** as a decimal (`float`).
- Birth year is an **approximation** — it doesn't account for whether the user's birthday has already occurred this year.
- Memory addresses (`id()`) will differ on every run and every machine; the values shown in the example output are illustrative only.

---

## 📌 8. How to Run

```bash
python fundamental_booster.py
```

You'll be prompted for your name, age, height, and favourite number, and the program will print a full summary along with each variable's type and memory address.

---

## 📌 10. Summary

This project is:

- A hands-on refresher on **Python fundamentals**
- Focused on `print()`, `input()`, **variables**, **operators**, and **type casting**
- A practical demonstration of `type()` and `id()` for inspecting data at runtime
- A stepping stone toward more advanced **Python Data Science** topics

---

*"Quality is our Motto."* — Red & White Skill Education, Shaping Skills for Scaling Higher.
