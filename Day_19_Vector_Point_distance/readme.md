# 📘 Linear Algebra Fundamentals  
## Distance, Norms, and Vector Operations

This README explains important Linear Algebra concepts including Euclidean Distance, Norms, Unit Vectors, Dot Product, and Cross Product with definitions, formulas, and applications.

---

## 🔹 Q.1 Euclidean Distance Formula (2D)

For two points:

P(x₁, y₁)  
Q(x₂, y₂)

The Euclidean distance is:

d = √[(x₂ − x₁)² + (y₂ − y₁)²]

It represents the shortest straight-line distance between two points in 2D space.

---

## 🔹 Q.2 Distance Formula (3D)

For two points:

P(x₁, y₁, z₁)  
Q(x₂, y₂, z₂)

Distance formula:

d = √[(x₂ − x₁)² + (y₂ − y₁)² + (z₂ − z₁)²]

---

## 🔹 Q.3 What is a Norm?

A norm is a function that measures the magnitude (length) of a vector.

Properties:
- Non-negative
- Equal to zero only for zero vector
- Scales with multiplication
- Follows triangle inequality

---

## 🔹 Q.4 L1 Norm (Manhattan Norm)

For vector v = (x₁, x₂, ..., xₙ)

||v||₁ = |x₁| + |x₂| + ... + |xₙ|

It calculates the sum of absolute values.

---

## 🔹 Q.5 L2 Norm (Euclidean Norm)

For vector v = (x₁, x₂, ..., xₙ)

||v||₂ = √(x₁² + x₂² + ... + xₙ²)

It represents the standard vector length.

---

## 🔹 Q.6 What is a Unit Vector?

A unit vector is a vector whose magnitude is 1.

Importance:
- Represents direction only
- Used in physics and graphics
- Helps in normalization

---

## 🔹 Q.7 How to Convert a Vector into Unit Vector?

Given vector v:

v̂ = v / ||v||

Steps:
1. Find magnitude of vector
2. Divide each component by magnitude

---

## 🔹 Q.8 Dot Product

For vectors:

u = (u₁, u₂, ..., uₙ)  
v = (v₁, v₂, ..., vₙ)

Dot product:

u · v = u₁v₁ + u₂v₂ + ... + uₙvₙ

Result: Scalar value

---

## 🔹 Q.9 Geometric Meaning of Dot Product

u · v = ||u|| ||v|| cosθ

Where θ is the angle between vectors.

Interpretation:
- Positive → angle < 90°
- Zero → perpendicular vectors
- Negative → angle > 90°

---

## 🔹 Q.10 Cross Product

Defined only in 3D.

For:

u = (u₁, u₂, u₃)  
v = (v₁, v₂, v₃)

u × v =

| i   j   k  |
| u₁  u₂  u₃ |
| v₁  v₂  v₃ |

Result: Vector

---

## 🔹 Q.11 Geometric Meaning of Cross Product

- Produces vector perpendicular to both vectors
- Magnitude:

||u × v|| = ||u|| ||v|| sinθ

- Represents area of parallelogram formed by two vectors
- Direction follows Right-Hand Rule

---

## 🔹 Q.12 Real-Life Applications

Dot Product:
Work = Force · Displacement

Cross Product:
Torque = r × F

---

## 📌 Applications of These Concepts

- Machine Learning
- Data Science
- Computer Graphics
- Physics
- Engineering
- Artificial Intelligence

---

## ✅ Conclusion

Distance formulas, norms, and vector operations form the foundation of linear algebra and are essential for advanced mathematical and computational applications.