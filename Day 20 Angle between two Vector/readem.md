# 📘 Linear Algebra Concepts  
## Angles, Projection, Geometry & Matrix Fundamentals

This README explains important Linear Algebra concepts including angle between vectors, projection, geometric representations (line, plane, hyperplane), and matrix fundamentals.

---

## 🔹 Q.1 What is the formula to calculate the angle between two vectors?

For vectors **u** and **v**, the angle θ between them is:

θ = cos⁻¹ ( (u · v) / (||u|| ||v||) )

Where:
- u · v = dot product
- ||u|| = magnitude of vector u
- ||v|| = magnitude of vector v

---

## 🔹 Q.2 How does the dot product relate to the angle between two vectors?

The dot product formula:

u · v = ||u|| ||v|| cosθ

This shows that the dot product directly depends on the cosine of the angle between vectors.

---

## 🔹 Q.3 How does cosine measure similarity between vectors?

cosθ determines similarity:

- cosθ = 1 → vectors are identical direction
- cosθ = 0 → vectors are perpendicular
- cosθ = −1 → vectors are opposite direction

In Machine Learning, this is called **Cosine Similarity**.

Higher cosine value → Higher similarity.

---

## 🔹 Q.4 Define Vector Projection

Vector projection is the projection of one vector onto another vector.

It represents how much of one vector lies in the direction of another.

---

## 🔹 Q.5 Difference Between Scalar and Vector Projection

Scalar Projection (Component):

compᵥ(u) = (u · v) / ||v||

Result: Scalar value (length only)

Vector Projection:

projᵥ(u) = (u · v / ||v||²) v

Result: Vector in direction of v

---

## 🔹 Q.6 Practical Application of Vector Projection

Physics:
Work done = Projection of force in direction of displacement.

Machine Learning:
Cosine similarity in text similarity, recommendation systems, and NLP.

---

## 🔹 Q.7 Define a Line in Geometry

A line is a one-dimensional set of points extending infinitely in both directions.

Vector form of line in 2D or 3D:

r = r₀ + t v

Where:
- r₀ = point on line
- v = direction vector
- t = scalar parameter

---

## 🔹 Q.8 Define a Plane in 3D Space

A plane is a two-dimensional flat surface extending infinitely.

General equation:

ax + by + cz + d = 0

Difference from line:
- Line → 1 dimension
- Plane → 2 dimensions

---

## 🔹 Q.9 What is a Hyperplane?

A hyperplane is a generalization of a plane in higher dimensions.

In n-dimensional space:

w · x + b = 0

Importance in Machine Learning:
- Used in Support Vector Machines (SVM)
- Separates data into different classes
- Decision boundary in classification problems

---

## 🔹 Q.10 Define a Matrix

A matrix is a rectangular arrangement of numbers in rows and columns.

Example:

A = [ a₁₁  a₁₂  
      a₂₁  a₂₂ ]

Difference:
- Vector → Single row or column
- Matrix → Multiple rows and columns

---

## 🔹 Q.11 Main Types of Matrices

1. Square Matrix → Same number of rows and columns
2. Diagonal Matrix → Non-zero elements only on main diagonal
3. Identity Matrix → Diagonal elements = 1
4. Zero Matrix → All elements are zero
5. Row Matrix → Single row
6. Column Matrix → Single column

---

## 🔹 Q.12 Common Matrix Operations

1. Addition:
A + B (same dimensions required)

2. Subtraction:
A − B (same dimensions required)

3. Multiplication:
A × B (columns of A = rows of B)

4. Transpose:
Aᵀ → Rows become columns

---

# 🚀 Applications

These concepts are widely used in:

- Machine Learning
- Artificial Intelligence
- Computer Graphics
- Data Science
- Engineering
- Physics

---

# ✅ Conclusion

Understanding angles between vectors, projections, geometric structures, and matrix operations forms the mathematical foundation for advanced topics such as:

- Optimization
- Deep Learning
- Computer Vision
- Statistical Modeling

These are core building blocks of modern computational systems.