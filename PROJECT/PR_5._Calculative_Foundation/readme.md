# 📊 Calculative Foundation

![Linear Algebra](https://img.shields.io/badge/Mathematics-Linear%20Algebra-blue)
![Language](https://img.shields.io/badge/Implementation-Python%20%7C%20Excel%20%7C%20Manual-yellow)
![Status](https://img.shields.io/badge/Status-Academic%20Project-success)

---

# 📌 Project Title
## Calculative Foundation

### 📖 Overview

The **Calculative Foundation** project focuses on applying **Linear Algebra concepts** to analyze and transform a dataset containing **students' academic performance scores across multiple subjects**.

This project integrates important mathematical concepts such as:

- Vectors
- Matrices
- Matrix Decomposition
- Eigenvalues & Eigenvectors
- Dimensionality Reduction Techniques

These concepts form the **core mathematical foundation of modern Data Science, Artificial Intelligence, Machine Learning, and Engineering systems**.

The project includes **both theoretical understanding and practical implementation** using computational tools.

---

# 🎯 Objective

The primary objective of this project is to:

- Understand **data representation using vectors and matrices**
- Apply **vector operations and matrix algebra**
- Explore **matrix decomposition techniques**
- Implement **dimensionality reduction algorithms**
- Interpret **eigenvalues and eigenvectors**
- Develop practical skills used in **Data Science and Machine Learning**

---

# 🧠 Problem Statement

A **research institute** has provided a dataset that contains **students' performance scores in multiple subjects**.

As a **data analyst**, your task is to analyze this dataset using **Linear Algebra techniques** to extract meaningful insights.

The following mathematical operations must be applied:

1. Represent the dataset using **vectors and matrices**
2. Perform **vector operations**
3. Apply **matrix operations**
4. Perform **matrix decompositions**
5. Use **dimensionality reduction techniques**
6. Interpret mathematical results in terms of **data insights**

The tasks must be completed **within the allotted duration of 6 hours** using **theoretical explanations and practical implementation**.

---

# 🧩 Project Tasks

---
# 🔹 Part A: Vector & Matrix Fundamentals

## 1️⃣ Represent Student Scores as Vectors

**Concept:**  
A vector is a list of numbers representing a student's scores in multiple subjects.

**Example**

Student A = (Math, Physics, Chemistry)

Numeric Example:

A = (85, 90, 78)  
B = (80, 88, 92)  
C = (75, 85, 89)

Each vector represents **one student's performance across subjects**.

---

## 2️⃣ Vector Operations

### Norm-1 (Manhattan Norm)

**Concept:**  
Measures the total absolute value of vector elements.

**Formula**

||x||₁ = Σ |xᵢ|

---

### Norm-2 (Euclidean Norm)

**Concept:**  
Measures the length or magnitude of a vector.

**Formula**

||x||₂ = √(Σ xᵢ²)

---

### Dot Product

**Concept:**  
Measures similarity between two vectors.

**Formula**

A · B = Σ (Aᵢ × Bᵢ)

---

### Angle Between Two Vectors

**Concept:**  
Shows how similar two vectors are.

**Formula**

cosθ = (A · B) / (||A|| × ||B||)

---

### Cross Product (3D Vector)

**Concept:**  
Produces a vector perpendicular to two 3D vectors.

**Formula**

A × B = | i  j  k ; A₁ A₂ A₃ ; B₁ B₂ B₃ |

---

## 3️⃣ Vector Projection

**Concept:**  
Projection shows how much one vector lies in the direction of another.

**Formula**

Projᵦ(A) = (A · B / ||B||²) B

---

# 🔹 Part B: Matrix Operations

## 4️⃣ Construct Dataset Matrix

**Concept:**  
A matrix represents students' scores in tabular form.

Example Matrix:

X =
[85 90 78  
80 88 92  
75 85 89]

Rows → Students  
Columns → Subjects

---

### Matrix Addition

**Concept:**  
Add corresponding elements of two matrices.

**Formula**

C = A + B

---

### Matrix Multiplication

**Concept:**  
Multiply rows of the first matrix with columns of the second matrix.

**Formula**

C[i][j] = Σ (A[i][k] × B[k][j])

---

### Transpose of Matrix

**Concept:**  
Transpose swaps rows and columns.

**Formula**

Aᵀ

---

### Matrix Inverse

**Concept:**  
Inverse matrix reverses the effect of the original matrix.

**Formula**

A × A⁻¹ = I

---

### Determinant

**Concept:**  
Determinant checks if a matrix is invertible.

**Formula**

|A| = a(ei − fh) − b(di − fg) + c(dh − eg)

---

# 🔹 Part C: Linear Transformations & Geometry

## 5️⃣ Lines, Planes, and Hyperplanes

**Concept:**  
Data dimensions can be represented geometrically.

| Dimension | Representation |
|-----------|---------------|
| 1D | Line |
| 2D | Plane |
| 3D | 3D Space |
| nD | Hyperplane |

Example:

2 Subjects → 2D Plane  
3 Subjects → 3D Space  
Many Subjects → Hyperplane

---

## 6️⃣ Dimensional Growth

**Concept:**  
As the number of features increases, the dimensional space increases.

Example:

2D → 3D → nD Space

Hyperplanes help create **decision boundaries in machine learning**.

---

# 🔹 Part D: Eigenvalues & Decomposition

## 7️⃣ Eigenvalues & Eigenvectors

**Concept:**  
Eigenvectors show directions of variance and eigenvalues show the magnitude.

**Formula**

Av = λv

---

## 8️⃣ LU Decomposition

**Concept:**  
A matrix can be decomposed into lower and upper triangular matrices.

**Formula**

A = L × U

---

## 9️⃣ Singular Value Decomposition (SVD)

**Concept:**  
SVD decomposes a matrix into three matrices to analyze data structure.

**Formula**

A = U Σ Vᵀ

---

# 🔹 Part E: Dimensionality Reduction

## 🔟 Principal Component Analysis (PCA)

**Concept:**  
PCA reduces dataset dimensions while keeping maximum variance.

**Formula**

Z = XW

Where:

X = Data matrix  
W = Principal components

---

## 1️⃣1️⃣ Linear Discriminant Analysis (LDA)

**Concept:**  
LDA separates data into different classes by maximizing class separation.

**Formula**

LDA = (Between-Class Variance) / (Within-Class Variance)

---

# 🛠 Tools & Technologies

The project can be implemented using:

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Excel
- Manual Calculations

---

# 📊 Expected Learning Outcomes

After completing this project, students will understand:

- Vector representation of data
- Matrix algebra operations
- Geometric interpretation of datasets
- Matrix decomposition methods
- Dimensionality reduction techniques
- Mathematical foundations of Data Science

---

# 🚀 Real-World Applications

These concepts are widely used in:

- Artificial Intelligence
- Machine Learning
- Data Science
- Computer Vision
- Recommender Systems
- Image Processing
- Natural Language Processing

---

# 👤 Author

Ayush Isamaliya

> GitHub:
https://github.com/isamaliya16

> LinkedIn: 
https://www.linkedin.com/in/ayush-isamaliya-686533312/
---

# 📜 License

This project is licensed under the **MIT License**.

---