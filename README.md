# Chapter 5 — Functions

---

## 🔹 Real-World Connection

When you open an app, play a game, or use a website, you are interacting with many small tasks happening behind the scenes.

* A login system checks your username and password
* A shopping cart calculates your total
* A game updates your score

Each of these tasks is handled by a **function**.

Instead of writing one massive program, developers break problems into smaller pieces. This is called **modular programming** or **divide and conquer**.

---

## 🔹 What is a Function?

A function is a block of code that performs a specific task.

Instead of writing the same code over and over, you:

* write it once
* give it a name
* call it when needed

---

### 🧠 Knowledge Check

What keyword is used to define a function in Python?

* function
* func
* def

<details>
<summary>👉 Click to reveal answer</summary>

✅ **Correct Answer: def**

</details>

---

## 🔹 Defining and Calling a Function

Example:
def greet():
print("Hello, welcome to programming!")

Calling the function:
greet()

When a function is called:

1. Python jumps to the function
2. Executes the code
3. Returns back to the program

---

### ▶️ Practice 1 — Creating and Calling a Function

👉 [Go to Practice 1](./chapter5_practice.py#L15)

---

## 🔹 Parameters and Arguments

Functions can accept data.

Example:
def greet(name):
print("Hello", name)

```
greet("Deaven")
```

* `name` is the parameter
* `"Deaven"` is the argument

---

### 🧠 Knowledge Check

What is the value passed into a function called?

* Parameter
* Argument
* Variable

<details>
<summary>👉 Click to reveal answer</summary>

✅ **Correct Answer: Argument**

</details>

---

### ▶️ Practice 2 — Function with a Parameter

👉 [Go to Practice 2](./chapter5_practice.py#L30)

---

## 🔹 Return Values

Some functions send data back using `return`.

Example:
def square(number):
return number * number

---

### 📊 IPO Chart Example

Function: square(number)

Input:      number
Processing: number * number
Output:     squared value

---

### 🧠 Knowledge Check

What keyword sends a value back from a function?

* send
* return
* output

<details>
<summary>👉 Click to reveal answer</summary>

✅ **Correct Answer: return**

</details>

---

### ▶️ Practice 3 — Value-Returning Function

👉 [Go to Practice 3](./chapter5_practice.py#L50)

---

## 🔹 Using Modules (Random Numbers)

Python includes built-in modules.

Example:
import random
print(random.randint(1, 6))

This simulates rolling a dice.

---

### 🧠 Knowledge Check

What module is used to generate random numbers?

* math
* random
* numbers

<details>
<summary>👉 Click to reveal answer</summary>

✅ **Correct Answer: random**

</details>

---

### ▶️ Practice 4 — Using the Random Module

👉 [Go to Practice 4](./chapter5_practice.py#L70)

---

## 🔹 Debugging Functions

Functions often break due to small mistakes:

* missing parentheses
* incorrect indentation
* missing parameters

Debugging is a critical skill.

---

### 🧠 Knowledge Check

Which of the following is a common error in functions?

* Indentation
* Missing colon
* Incorrect parameters
* All of the above

<details>
<summary>👉 Click to reveal answer</summary>

✅ **Correct Answer: All of the above**

</details>

---

### ▶️ Practice 5 — Debug the Function

👉 [Go to Practice 5](./chapter5_practice.py#L95)

---

# 🧠 Check Your Understanding

You should now understand:

* How to define and call functions
* How to pass data into functions
* How to return values
* How to debug functions

---

# 🚀 Now You Do (Independent Practice)

These are similar, but now you will complete them on your own.

---

## ▶️ Practice 6 — Create a Function

👉 [Go to Practice 6](./chapter5_practice.py#L130)

Create a function called `display_message`
Print: "Functions are powerful!"

---

## ▶️ Practice 7 — Parameter Practice

👉 [Go to Practice 7](./chapter5_practice.py#L150)

Create a function called `double_number`
Accept a number and print it doubled

---

## ▶️ Practice 8 — Return Values

👉 [Go to Practice 8](./chapter5_practice.py#L170)

Create a function called `cube_number`
Return the cube of a number

---

## ▶️ Practice 9 — Random Function

👉 [Go to Practice 9](./chapter5_practice.py#L190)

Create a function called `coin_flip`
Return "Heads" or "Tails"

---

## ▶️ Practice 10 — Debug Challenge

👉 [Go to Practice 10](./chapter5_practice.py#L210)

Fix the function so it works correctly

---

# 📌 Final Thoughts

Functions are one of the most important concepts in programming.

Every program you build from this point forward will use them.

Master this concept, and programming becomes much easier.
