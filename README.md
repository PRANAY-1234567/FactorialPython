# 📘 Factorial Using Recursion (Python)

## 📌 Overview

This Python program calculates the **factorial** of a number using **recursion**.

Factorial of a number `n` (written as `n!`) is:

[
n! = n × (n-1) × (n-2) × ... × 1
]

Example:

```
5! = 5 × 4 × 3 × 2 × 1 = 120
```

---

## ⚙️ Source Code

```python
def factorial(n):
    if n == 1:
        return 1
    else:
        return n * factorial(n - 1)

print(factorial(5))
```

---

## 🧠 How It Works

### 1️⃣ Function Definition

```python
def factorial(n):
```

Defines a function named `factorial` that takes one parameter `n`.

---

### 2️⃣ Base Case

```python
if n == 1:
    return 1
```

This stops the recursion.
Without a base case, recursion would continue forever.

---

### 3️⃣ Recursive Case

```python
return n * factorial(n - 1)
```

The function calls itself with `n - 1`.

For `factorial(5)`, the calculation happens like this:

```
5 × factorial(4)
5 × 4 × factorial(3)
5 × 4 × 3 × factorial(2)
5 × 4 × 3 × 2 × factorial(1)
5 × 4 × 3 × 2 × 1
```

Final result:

```
120
```

---

## ▶️ Output

```
120
```

---

## 🔑 Key Concepts Demonstrated

* Function definition
* Recursion
* Base case
* Mathematical logic implementation

---

## ⚠️ Important Note

For better practice, factorial should also handle `0`:

```python
if n == 0 or n == 1:
    return 1
```

Because:

```
0! = 1
```

---

## 🚀 Use Cases

* Mathematical computations
* Algorithm design
* Interview coding questions
* Understanding recursion concepts

---

## 📚 Learning Outcome

After understanding this program, you should know:

* What recursion is
* Why a base case is important
* How recursive function calls work step-by-step

---

👨‍💻 Created for Python recursion practice.


<img width="561" height="640" alt="image" src="https://github.com/user-attachments/assets/aa81976f-1e5b-4a1c-9e0a-46e4be73d55d" />
