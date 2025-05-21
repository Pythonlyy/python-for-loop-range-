# 🔁 Using `for` Loops with `range()` in Python

Loops let you repeat actions. `for` loops are perfect when you know how many times something should run. Combine them with `range()` to count like a pro.

---

## 💡 What You'll Learn

* How `range()` generates a sequence of numbers
* How to use a `for` loop to repeat actions
* What `for i in range(n)` really means

---

## 🔢 What is `range()`?

```python
range(5)  # → 0, 1, 2, 3, 4
```

It starts at 0 by default and goes **up to but not including** the number you give it.

---

## 💻 Example with Explanation

```python
for i in range(5):
    print(i)
```

### 🔈 Output

```
0
1
2
3
4
```

This repeats the `print(i)` line 5 times. Each time, `i` gets the next number from `range(5)`.

---

## 📌 Key Notes

* Loops need **indentation** after the `:`
* The variable (`i`) changes on every loop
* Use `_` if you don’t need the variable

---

## 🧪 Try It Yourself

Print "Hello!" 3 times:

```python
for _ in range(3):
    print("Hello!")
```

### 🔈 Expected Output

```
Hello!
Hello!
Hello!
```

---

🐍 This is part of the **Pythonly** beginner series.
Learn Python one line at a time. Follow **@Pythonly** for more.

---

