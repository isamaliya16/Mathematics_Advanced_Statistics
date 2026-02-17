# 📊 Covariance & Correlation — 

## Overview

This README provides **detailed conceptual explanations, manual calculations, and Python implementations** for key statistical topics including **covariance**, **Pearson correlation**, and **Spearman rank correlation**. It is designed as a structured learning guide for students practicing statistics with Python.

---

## 🎯 Learning Objectives

After completing this guide, you will be able to:

- Understand covariance and correlation concepts
- Interpret statistical relationships
- Perform manual calculations
- Implement solutions using Python
- Compare Pearson and Spearman methods

---

# 📚 Questions with Detailed Answers

---

## ✅ Q1 — Define Covariance

### Answer
Covariance measures how two variables change **together**.

Formula:

Cov(X,Y) = Σ[(Xi − X̄)(Yi − Ȳ)] / n

### Interpretation

- **Positive covariance** → variables move in the same direction
- **Negative covariance** → variables move in opposite directions
- **Zero covariance** → no linear relationship

---

## ✅ Q2 — Covariance vs Correlation

### Covariance
- Shows direction of relationship
- Depends on measurement scale

### Correlation
- Standardized covariance
- Range: −1 to +1
- Scale independent

### Why correlation is preferred
Because it provides **strength + direction** in a normalized, interpretable form.

---

## ✅ Q3 — Python Function for Covariance

```python
import numpy as np

def covariance(x, y):
    mean_x = np.mean(x)
    mean_y = np.mean(y)
    return np.mean((x - mean_x) * (y - mean_y))

x = np.array([1,2,3])
y = np.array([4,5,6])
print("Covariance:", covariance(x,y))
```

---

## ✅ Q4 — Manual Covariance Calculation

Given:

X = [2,4,6,8]
Y = [1,3,2,5]

Means:

X̄ = 5
Ȳ = 2.75

| Xi | Yi | Xi−X̄ | Yi−Ȳ | Product |
|----|----|-------|------|---------|
|2|1|-3|-1.75|5.25|
|4|3|-1|0.25|-0.25|
|6|2|1|-0.75|-0.75|
|8|5|3|2.25|6.75|

Sum = 11

Covariance = 11 / 4 = **2.75**

---

## ✅ Q5 — Pearson Correlation

Pearson correlation measures **linear relationship strength**.

Range:

- +1 → perfect positive
- −1 → perfect negative
- 0 → no linear relation

Formula:

r = Cov(X,Y) / (σx σy)

---

## ✅ Q6 — Interpret r = −0.95

A value of −0.95 indicates:

- Very strong negative linear relationship
- As one variable increases, the other almost always decreases

---

## ✅ Q7 — Pearson Correlation in Python

```python
from scipy.stats import pearsonr

x = [2,4,6,8]
y = [1,3,2,5]

r, p = pearsonr(x,y)
print("Pearson r:", r)
print("p-value:", p)
```

---

## ✅ Q8 — When to Use Spearman Correlation

Use Spearman when:

- Data is ordinal/ranked
- Relationship is monotonic but not linear
- Outliers exist

It compares **rank positions**, not raw values.

---

## ✅ Q9 — Suitable Data for Spearman

Best for ranked or ordered data.

Example:

Student rank vs satisfaction rating.

Spearman checks if higher ranks correspond to higher ratings.

---

## ✅ Q10 — Manual Spearman Calculation

X = [20,18,22,20]
Y = [60,65,58,62]

### Step 1 — Rank values

X ranks → [2.5,1,4,2.5]
Y ranks → [2,4,1,3]

### Step 2 — Difference & square

|Rx|Ry|d|d²|
|--|--|--|--|
|2.5|2|0.5|0.25|
|1|4|-3|9|
|4|1|3|9|
|2.5|3|-0.5|0.25|

Σd² = 18.5

n = 4

Spearman formula:

ρ = 1 − [6Σd² / n(n²−1)]

ρ = 1 − (6×18.5)/(4×15)
ρ = 1 − 111/60
ρ = **−0.85** (approx)

---

## ✅ Q11 — Spearman Interpretation

- 1 → perfect increasing rank relation
- −1 → perfect decreasing rank relation
- 0 → no monotonic relation

---

## ✅ Q12 — Python Comparison Example

```python
from scipy.stats import pearsonr, spearmanr

x = [10,20,30,40,50]
y = [8,18,28,35,60]

p_corr, _ = pearsonr(x,y)
s_corr, _ = spearmanr(x,y)

print("Pearson:", p_corr)
print("Spearman:", s_corr)
```

---

## 🛠 Tools Required

- Python 3.x
- NumPy
- SciPy

Install:

```bash
pip install numpy scipy
```

---

## 🚀 How to Practice

1. Understand the concept
2. Solve manually
3. Verify using Python
4. Interpret results

---

## 💡 Skills Developed

- Statistical reasoning
- Numerical computation
- Python programming
- Analytical thinking

---

## 👤 Author

Ayush Isamaliya  
Python & Data Science Enthusiast  
India

---

Happy Learning! 🚀
