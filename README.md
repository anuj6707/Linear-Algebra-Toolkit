# Linear Algebra Toolkit

A command-line based Linear Algebra Toolkit built using Python and NumPy.
This project allows users to perform core matrix operations and solve linear systems interactively.

---

## 🚀 Features

* Matrix Addition & Subtraction
* Matrix Multiplication
* Transpose of Matrices
* Determinant Calculation
* Matrix Inverse (if exists)
* Rank of Matrix
* Solve Linear Equations (AX = B)

---

## 🛠️ Tech Stack

* Python
* NumPy

---

## 📂 Project Structure

* `main.py` – main program with menu-driven interface

---

## ▶️ How to Run

1. Make sure Python is installed
2. Install NumPy:

   ```
   pip install numpy
   ```
3. Run the program:

   ```
   python main.py
   ```

---

## 🧠 How It Works

* User inputs dimensions and values for two matrices (A and B)
* The program performs operations based on user selection
* Conditions are checked before operations (e.g., dimension match, invertibility)

---

## ⚠️ Constraints & Validations

* Addition/Subtraction require same matrix dimensions
* Multiplication requires columns of A = rows of B
* Inverse exists only if matrix is square and determinant ≠ 0
* Solving AX = B requires A to be square and compatible with B

---

## 📌 What I Learned

* Working with NumPy for matrix operations
* Handling matrix conditions and edge cases
* Implementing a menu-driven CLI system
* Understanding linear algebra operations programmatically

---

## 🔮 Future Improvements

* Better formatted output
* Support for dynamic matrix selection
* Error handling improvements
* Add graphical interface (GUI)
* Extend to larger matrix operations

---
