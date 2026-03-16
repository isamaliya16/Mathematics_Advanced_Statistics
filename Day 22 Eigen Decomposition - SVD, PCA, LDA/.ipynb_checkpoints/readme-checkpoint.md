# Linear Algebra Concepts in Machine Learning

## Q1. What is Singular Value Decomposition (SVD) in Linear Algebra?

Singular Value Decomposition (SVD) is a matrix factorization technique used in linear algebra.  
It decomposes any matrix **A** into three matrices:

A = U Σ Vᵀ

Where:
- **U** = Left singular vectors (orthogonal matrix)
- **Σ (Sigma)** = Diagonal matrix containing singular values
- **Vᵀ** = Transpose of right singular vectors

SVD helps analyze the structure of a matrix and is widely used in data science, machine learning, and signal processing.

---

## Q2. How is SVD different from Eigenvalue Decomposition?

| Feature | SVD | Eigenvalue Decomposition |
|------|------|------|
| Matrix Type | Works for any matrix (rectangular or square) | Works only for square matrices |
| Output | U, Σ, Vᵀ | Eigenvectors and Eigenvalues |
| Stability | More stable numerically | Less stable for some matrices |
| Usage | Data compression, recommendation systems | Matrix analysis, PCA |

---

## Q3. What are the three matrices obtained from SVD (U, Σ, Vᵀ), and what do they represent?

1. **U Matrix**
   - Contains left singular vectors.
   - Represents the relationship between rows of the original matrix.

2. **Σ (Sigma) Matrix**
   - Diagonal matrix containing singular values.
   - Indicates the importance or strength of each component.

3. **Vᵀ Matrix**
   - Transpose of matrix V.
   - Contains right singular vectors representing column relationships.

---

## Q4. Mention one application of SVD in data compression or recommendation systems.

One common application is **recommendation systems**.

Example:
- Movie recommendation platforms like Netflix use SVD to analyze user–movie rating matrices.
- It helps predict which movies a user might like based on patterns in the data.

---

## Q5. What is Principal Component Analysis (PCA), and what is its main purpose?

Principal Component Analysis (PCA) is a statistical technique used to transform high-dimensional data into a smaller number of variables called **principal components**.

Main purpose:
- Reduce the number of variables while preserving as much information as possible.

---

## Q6. How does PCA use eigenvalues and eigenvectors?

PCA computes the **covariance matrix** of the dataset and then calculates:

- **Eigenvectors** → Direction of maximum variance
- **Eigenvalues** → Amount of variance in that direction

The eigenvectors with the largest eigenvalues are selected as principal components.

---

## Q7. What does the first principal component represent in PCA?

The **first principal component** represents the direction in which the data varies the most.  
It captures the **maximum variance** present in the dataset.

---

## Q8. Why is PCA often used for dimensionality reduction?

PCA reduces dimensionality because:

- It removes redundant or correlated features
- It keeps only the most important components
- It simplifies datasets
- It improves machine learning model performance and speed

---

## Q9. What are some limitations of PCA?

Some limitations include:

- PCA assumes linear relationships in data
- Sensitive to scaling of variables
- Difficult to interpret principal components
- May lose useful information during dimensionality reduction

---

## Q10. What is Linear Discriminant Analysis (LDA), and how does it differ from PCA?

Linear Discriminant Analysis (LDA) is a supervised machine learning technique used for **classification and dimensionality reduction**.

Difference between PCA and LDA:

| Feature | PCA | LDA |
|------|------|------|
| Type | Unsupervised | Supervised |
| Goal | Maximize variance | Maximize class separation |
| Uses Labels | No | Yes |

---

## Q11. How does LDA maximize class separability in data?

LDA works by:

1. Maximizing **between-class variance**
2. Minimizing **within-class variance**

This creates a projection where different classes are as far apart as possible.

---

## Q12. Mention one practical application of LDA in machine learning

One common application is **face recognition systems**.

LDA helps distinguish different individuals by maximizing the separation between face classes.