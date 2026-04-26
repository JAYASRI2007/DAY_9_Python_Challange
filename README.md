# 🧠 Day 9 Python Challenge

## Shallow Copy vs Deep Copy (with Real-World Inventory Example)

---

## 📌 Overview

This project demonstrates the difference between **Shallow Copy** and **Deep Copy** in Python using a realistic **inventory management system**.

It shows how data behaves when copied and modified, and highlights the importance of memory references in nested data structures.

---

## 🚀 Features

* Create a nested inventory dataset (list of dictionaries)
* Apply discounts and stock updates
* Compare original vs modified data
* Demonstrate:

  * Shallow Copy behavior
  * Deep Copy behavior
* Memory reference verification using `is` operator

---

## 🛠️ Technologies Used

* Python 3
* Built-in `copy` module

---

## 📂 Project Structure

```
DAY_9/
│── day_9.py
│── README.md
```

---

## 🔍 Key Concepts

### 🔹 Shallow Copy

* Copies only the outer structure
* Inner objects (nested dictionaries) are **shared**
* Changes in copy → affect original

### 🔹 Deep Copy

* Copies everything recursively
* Completely independent objects
* Changes do **not** affect original

---

## ⚙️ How It Works

1. Create inventory data
2. Generate:

   * Shallow copy
   * Deep copy
3. Apply:

   * 10% price discount
   * Stock modification (based on roll number)
4. Compare results
5. Verify memory sharing

---

## 📊 Sample Output

```
--- MEMORY PROOF ---
Shallow shares nested object?: True
Deep shares nested object?: False
```

---

## ⚠️ Important Note

Due to shallow copy behavior, modifying the shallow copy also updates the original data.
This can affect comparison results if not handled carefully.

---

## ▶️ How to Run

```bash
python day_9.py
```

OR

```bash
py day_9.py
```

---

## 🎯 Learning Outcome

After this project, you will understand:

* Difference between shallow and deep copy
* How Python handles memory references
* Why deep copy is important for nested data

---

## 💡 Real-World Use Cases

* Data processing
* APIs and backend systems
* Avoiding unintended data mutation
* Working with complex JSON structures

---

## 👩‍💻 Author

**Jayasri**

---

## ⭐ If you found this useful

Give this repo a ⭐ on GitHub!
