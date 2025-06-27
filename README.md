# Optimization-Model
COMPANY: CODTECH IT SOLUTIONS

NAME: ANIKET BHOGE

INTERN ID:CT06DF1221

DOMAIN: DATA SCIENCE

DURATION: 6 WEEKS

MENTOR: NEELA SANTOSH
# 🧮 Product Mix Optimization using Linear Programming in Python

This repository contains a Jupyter Notebook that demonstrates solving a business optimization problem using **Linear Programming (LP)** with **Python (PuLP)** and **Matplotlib**.

---

## 📌 Problem Statement

A company manufactures **two products** — Product A and Product B. Each product requires limited resources (machine and labor hours), and generates a known profit. The objective is to determine how many units of each product to produce to **maximize total profit**, without exceeding available resources.

---

## 📊 Business Data

| Resource       | Product A | Product B | Available |
|----------------|-----------|-----------|-----------|
| Machine Hours  | 3 hrs     | 2 hrs     | 120 hrs   |
| Labor Hours    | 2 hrs     | 1 hr      | 100 hrs   |

- 💰 Profit for Product A: ₹30/unit  
- 💰 Profit for Product B: ₹20/unit

---

## ✅ Objective

Maximize profit:  
**Z = 30x + 20y**

Subject to constraints:

- 3x + 2y ≤ 120 (Machine hours)  
- 2x + y ≤ 100 (Labor hours)  
- x ≥ 0, y ≥ 0 (Non-negativity)

---

## 🧪 Solution Approach

- Formulated the problem as a linear programming model.
- Used **PuLP** library to define decision variables, constraints, and the objective function.
- Solved the problem using `model.solve()`.
- Visualized constraints and optimal solution using **Matplotlib**.

---

## 📌 Results

- ✅ Optimal units of Product A: **20**
- ✅ Optimal units of Product B: **60**
- 💰 **Maximum Profit**: ₹**1800**
- 🎯 Feasible region and constraints plotted to show the optimal point.

---

## 📁 Files Included

- `product_mix_optimization.ipynb` – Jupyter Notebook with problem setup, code, and visualization.
- `README.md` – Project documentation.

---

## 🚀 Technologies Used

- Python 🐍
- PuLP 📦
- Matplotlib 📊
- Jupyter Notebook 📒

---

## 📌 How to Run

1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install pulp matplotlib
3. Open the notebook:
   ```bash
   jupyter notebook product_mix_optimization.ipynb
   
