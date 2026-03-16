# 📊 Loan Application Analysis

[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/) 
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)](https://jupyter.org/) 
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## 🚀 Project Overview

**Project Type:** Python CLI / Jupyter Notebook  
**Language:** Python 3  
**Framework / Tools:** Pandas, NumPy, Matplotlib, Seaborn, SciPy  
**Purpose:** Evaluate loan default risk using statistical and probability analysis  
**Target Audience:** Students, Data Science Enthusiasts, Portfolio  

This project demonstrates a comprehensive statistical analysis on a loan application dataset (~5000 records). It covers both **theory** and **practical Python implementation** to provide insights into customer behavior and default risk prediction.

---

## 📁 Dataset

**Filename:** `loan_applications.csv`  
**Source:** Generated using an AI tool  
**Fields:**

| Column Name      | Description                               |
|-----------------|-------------------------------------------|
| Customer_ID      | Unique customer identifier                |
| Age              | Age of the customer (years)               |
| Income           | Annual income (in $)                      |
| Loan_Amount      | Loan amount requested (in $)              |
| Credit_Score     | Credit score (300–850)                     |
| Loan_Term        | Loan term in months                        |
| Default_Status   | Loan default status (`Yes` / `No`)       |

---

## 📝 Problem Statement

You are required to:

1. Explain key statistical concepts in theory.
2. Apply Python-based statistical and probability analysis to evaluate **loan default risk**.
3. Derive actionable insights that can help financial institutions make informed decisions.

---

## 🧩 Exam Tasks

### Part A – Theory

1. Explain **Mean, Median, Mode** in the context of customer income.  
2. Differentiate between **Standard Deviation** and **Variance** using loan amounts.  
3. Define a **Random Variable** with an example from the dataset.  
4. Explain **Conditional Probability** in terms of loan defaults.  
5. Define **Bayes Theorem** and describe how banks can apply it.  
6. Differentiate between **Empirical Probability** and **Theoretical Probability** with examples.  
7. Explain **Poisson Distribution** with a business example.  
8. Write a short note on **Eigenvalues and Eigenvectors** in data analysis.

---

### Part B – Practical (Python Programming)

#### **Step 1 – Central Tendency & Dispersion**
- Calculate mean, median, and mode of `Income`.
- Calculate range, variance, and standard deviation of `Loan_Amount`.

#### **Step 2 – Probability & Events**
- Compute probability of loan default.
- Create a contingency table between `Default_Status` and `Credit_Score` (categorized into ranges).  
- Compute conditional probability: P(Default | Credit_Score < 600).

#### **Step 3 – Distributions & Visualization**
- Plot a **Histogram** of `Credit_Score` with Gaussian curve overlay.
- Check **Skewness** and **Kurtosis** of `Loan_Amount`.
- Draw a **Q-Q Plot** for `Income`.

#### **Step 4 – Linear Algebra Applications**
- Take the first 5 customers’ `[Income, Loan_Amount]` as vectors.
- Perform **dot product** between two customer vectors.
- Find **Norm 2** of a customer’s financial vector.
- Calculate the **angle** between two customers’ vectors.

---

## 🛠️ Tools & Libraries

- **Python 3** – Core programming language  
- **NumPy** – Numerical computations  
- **Pandas** – Data manipulation  
- **Matplotlib & Seaborn** – Visualization  
- **SciPy** – Statistical functions  
- **Jupyter Notebook** – Interactive coding environment  

---

## 📊 Deliverables

1. **Python File / Jupyter Notebook** with all calculations.  
2. **Report (PDF/Word)** including:
   - Short theory answers (Part A)
   - Screenshots / outputs from Part B
3. **Insights** (examples):
   - Customers with Credit Score < 600 have a **65% chance of default**.  
   - Higher-income customers tend to have longer loan terms.  
   - Skewness in Loan_Amount indicates few very large loans.  

---

## 📈 Insights & Analysis

- Conditional probabilities help identify high-risk customer segments.  
- Histograms and Q-Q plots reveal distribution patterns in financial data.  
- Vector operations can quantify similarity between customer profiles.

---
## 👤 Author

**Ayush Isamaliya**  
- GitHub: https://github.com/isamaliya16 
- LinkedIn: https://www.linkedin.com/in/ayush-isamaliya-686533312/
 
---

## 🏷️ License

This project is licensed under the **MIT License**.