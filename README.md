# Numpy-Fundamentals

# NumPy Fundamentals & Sudoku Validator 📊

A comprehensive collection of **NumPy** exercises and implementations demonstrating core Data Science concepts. This repository serves as a practical guide to array manipulation, linear algebra, and vectorized operations in Python.

It includes a **Mini-Project**: A fully functional **Sudoku Validator** that uses NumPy's efficient axis aggregation to verify puzzle solutions.

## 🚀 Key Concepts Covered

This notebook explores the power of the NumPy library through practical examples:

* **Array Creation:** Generating arrays using `arange`, `linspace`, `zeros`, `ones`, and random sampling.
* **Dimensions & Shapes:** Understanding `reshape`, `resize`, and matrix dimensions.
* **Indexing & Slicing:** Advanced techniques including Boolean Indexing and Matrix slicing.
* **Vectorized Operations:** Arithmetic operations, Broadcasting, and Matrix Multiplication (`@` operator).
* **Data Manipulation:** Stacking (`vstack`, `hstack`) and Splitting (`vsplit`, `hsplit`) arrays.
* **Linear Algebra:** Dot products, Transpose, and aggregation functions (`mean`, `std`, `sum`).

## 🧠 Mini-Project: Sudoku Validator

At the end of the notebook, I implemented a logic-based validator for a 9x9 Sudoku puzzle.

**Logic Implemented:**
1.  **Row Validation:** Checks if the sum of every row equals 45 (sum of 1-9).
2.  **Column Validation:** Checks if the sum of every column equals 45.
3.  **Sub-grid (3x3) Validation:** Iterates through 3x3 blocks to ensure each contains all unique digits.

```python
# Snippet from the project
for i in range(0, 9, 3):
    for j in range(0, 9, 3):
        block = sudoku_grid[i:i+3, j:j+3]
        # Validates that every 3x3 block sums to 45

🛠️ Tech Stack
Language: Python 3.13.3
Library: NumPy
Environment: Jupyter Notebook / Google Colab
