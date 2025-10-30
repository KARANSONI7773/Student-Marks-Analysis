# 🎯 NumPy Statistical & Math Functions – Mini Project

## 🧩 Project Overview
This project demonstrates how to use **NumPy** for performing **statistical** and **mathematical** operations on datasets — a fundamental step in **Data Science**.

We’ll analyze students’ marks and compute:
- Mean, Median, Variance, Standard Deviation
- Sum, Maximum, Minimum
- Index of Topper & Lowest Scorer
- Mathematical transformations (Square, Square Root)

---

## 🧠 Features
✅ Accepts marks input from the user  
✅ Uses NumPy arrays for fast computation  
✅ Applies statistical & math functions  
✅ Displays key metrics clearly  
✅ Beginner-friendly, modular code  

---

## 🧮 Example Code
```python
import numpy as np

# Step 1: Take marks input
marks = np.array(list(map(int, input("Enter marks of 5 students: ").split())))

# Step 2: Show basic info
print("\nMarks:", marks)
print("Total Students:", marks.size)

# Step 3: Apply statistical functions
print("\n--- Statistical Analysis ---")
print("Total Marks:", np.sum(marks))
print("Average Marks:", np.mean(marks))
print("Highest Marks:", np.max(marks))
print("Lowest Marks:", np.min(marks))
print("Standard Deviation:", np.std(marks))
print("Variance:", np.var(marks))
print("Median:", np.median(marks))
print("Index of Topper:", np.argmax(marks))
print("Index of Lowest Scorer:", np.argmin(marks))

# Step 4: Apply mathematical functions
print("\n--- Math Operations ---")
print("Square of Marks:", np.square(marks))
print("Square Root of Marks:", np.sqrt(marks))
