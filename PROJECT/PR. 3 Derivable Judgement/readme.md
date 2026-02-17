# 📊 Health Dataset Statistical Analysis Project

> 🚀 A complete inferential statistics project combining **theory + Python implementation** using a simulated health dataset.

This project demonstrates how statistical concepts are applied to real-world healthcare-style data using Python libraries.

---

# 🧠 Project Goals

✅ Understand inferential statistics  
✅ Apply hypothesis testing  
✅ Estimate population parameters  
✅ Compare group differences  
✅ Analyze categorical relationships  
✅ Study variable correlations  
✅ Interpret real statistical results  

---

# 📁 Dataset Overview

This synthetic dataset contains **1000 health records** designed for statistical learning.

### 🔍 Fields Included

| Field | Description |
|------|-------------|
🆔 Record ID | Unique identifier  
👤 Age | Age of individual  
📦 Weight | Body weight  
⚖ BMI | Body Mass Index  
🚻 Gender | Male/Female/Other  
🌍 Region | Geographic category  
🚬 Smoking Status | Lifestyle indicator  
🏃 Exercise Frequency | Activity level  
🩺 Blood Pressure | Health measure  
🩸 Diabetes | Disease indicator  
❤️ Hypertension | Health condition  
🧪 Cholesterol | Lab value  
🍬 Glucose | Blood sugar  
📅 Visit Date | Medical record date  

---

# 🧩 Part A — Theoretical Foundation

This section builds the conceptual understanding behind the analysis.

---

## 📌 1. Inferential Statistics

Inferential statistics allows us to make conclusions about a population using sample data.

**Idea**
 μ ≈ x̄
 
📖 Meaning: Sample statistics estimate unknown population parameters.

---

## 📌 2. Hypothesis Testing

A structured process to test assumptions about populations.

### Components

- H₀ → Null hypothesis  
- H₁ → Alternative hypothesis  
- α → Significance level  
- Test statistic  
- Decision rule  

**Formula**

Z = (x̄ − μ) / (σ / √n)
---

## 📌 3. Confidence Interval

Provides a likely range for a population parameter.
CI = x̄ ± t(α/2) × (s / √n)

✔ Higher confidence → wider interval

---

## 📌 4. p-value

Probability of observing results assuming H₀ is true.

👉 Rule:

```
Reject H₀ if p ≤ α
```

---

## 📌 5. Type I & Type II Errors

❌ Type I → False rejection  
❌ Type II → Missed detection  

Power = 1 − β

---
## 📌 6. Major Statistical Tests — Detailed Explanation

Statistical hypothesis tests are used to make decisions about populations based on sample data. Each test is designed for specific data conditions and research goals.

---

## 🔹 z-test

### ✅ Purpose
A z-test determines whether a sample mean significantly differs from a known population mean when:

- Sample size is **large** (n ≥ 30)
- Population variance is **known**

---

### 🧮 Formula
z = (x̄ − μ) / (σ / √n)
Where:

- x̄ = sample mean  
- μ = population mean  
- σ = population standard deviation
- n = sample size  
---

### 📊 Interpretation

- Large |z| → strong evidence against null hypothesis  
- Small |z| → insufficient evidence  

---

## 🔹 t-test

### ✅ Purpose
A t-test evaluates whether a sample mean differs from a population mean when:

- Sample size is **small** (n < 30)
- Population variance is **unknown**

---

### 🧮 Formula

t = (x̄ − μ) / (s / √n)
Where:

- s = sample standard deviation  
- other symbols same as z-test  

---

### 📊 Interpretation

- Compare t-value with critical t-table value  
- Larger deviation → reject null hypothesis  

---

## 🔹 Chi-square (χ²) Test

### ✅ Purpose
Tests the relationship between **categorical variables** or goodness-of-fit.

---

### 🧮 Formula
χ² = Σ[(O − E)² / E]
Where:

- O = observed value  
- E = expected value  

---

### 📊 Interpretation

- Large χ² → observed differs significantly from expected  
- Small χ² → differences likely due to chance  

---

## 🔹 ANOVA (Analysis of Variance)

### ✅ Purpose
Compares **three or more group means** to determine if at least one differs significantly.

---

### 🧮 Formula
F = MSbetween / MSwithin
Where:

- MS = mean square (variance estimate)

---

### 📊 Interpretation

- Large F → group means significantly differ  
- Small F → means likely similar  

---

## 🔍 Summary Table

| Test | Used For | Sample Condition | Key Idea |
|------|----------|----------------|----------|
| z-test | Mean comparison | Large sample, known variance | Standard normal distribution |
| t-test | Mean comparison | Small sample, unknown variance | Student’s t distribution |
| Chi-square | Categorical testing | Frequency data | Observed vs expected |
| ANOVA | Multiple mean comparison | ≥ 3 groups | Variance ratio |

---

## ✅ Conclusion

These statistical tests allow researchers to:

- Compare means  
- Analyze categorical data  
- Evaluate multi-group differences  
- Make evidence-based decisions  

Each test applies under specific assumptions and data types.

---


## 📌 7. Covariance

Measures joint variability.

Cov(X,Y) = Σ[(x − x̄)(y − ȳ)] / (n − 1)
---

## 📌 8. Correlation

Measures strength & direction.
−1 ≤ r ≤ 1
---

# 🔬 Part B — Data Analysis with Python

Libraries used:

🐍 NumPy  
📊 Pandas  
📈 SciPy  

---

## ✅ Task 1 — Hypothesis Formulation

### Smoking vs Diabetes
H₀ → No association  
H₁ → Association exists  

### Exercise vs Hypertension
H₀ → No effect  
H₁ → Effect exists  

---

## ✅ Task 2 — Confidence Intervals

Estimated population ranges for:

- Age  
- Weight  
- BMI  
- Blood pressure  

📌 Interpretation: True values likely fall inside intervals.

---

## ✅ Task 3 — Mean Hypothesis Test

Compared sample mean age to hypothesized value.

✔ Result → Significant difference  
👉 Decision → Reject H₀

---

## ✅ Task 4 — Independent t-test

BMI comparison:

👨 Male vs 👩 Female

✔ Result → No significant difference  
👉 Decision → Fail to reject H₀

---

## ✅ Task 5 — Chi-square Test

Smoking vs Diabetes relationship.

✔ Result → No strong statistical association.

---

## ✅ Task 6 — ANOVA

Age groups vs disease rate.

📌 Purpose → Detect group variation.

Decision based on p-value threshold.

---

## ✅ Task 7 — Covariance & Correlation

Age vs BMI relationship analysis.

✔ Positive → Increase together  
✔ Negative → Opposite trend  

---

## ✅ Task 8 — Final Decisions Summary

| Test | Decision | Meaning |
|------|----------|---------|
Mean Age Test | Reject H₀ | Significant difference |
Gender BMI Test | Accept H₀ | Similar averages |
Smoking vs Disease | Accept H₀ | Weak association |
Confidence Intervals | Valid | Reliable estimates |
ANOVA | Depends on p-value | Group comparison |
Correlation | Descriptive | Relationship insight |

---

# 📊 Statistical Workflow

```
Dataset → Hypothesis → Testing → Interpretation → Decision
```

---

# 🛠 Technology Stack

✔ Python  
✔ NumPy  
✔ Pandas  
✔ SciPy  

---

# ▶ How to Run

```bash
pip install numpy pandas scipy
python analysis.py
```

---

# 🎯 Learning Outcomes

After completing this project:

✅ Understand inferential statistics  
✅ Perform hypothesis testing  
✅ Interpret p-values  
✅ Compare group means  
✅ Analyze categorical data  
✅ Estimate population parameters  
✅ Study variable relationships  

---

# 📌 Key Takeaway

This project bridges **statistical theory** and **practical Python analysis**, demonstrating how data-driven decisions are made in real-world scenarios.

---

# ⭐ Project Highlights

📈 Real statistical testing  
🧠 Concept + implementation  
📊 Health data simulation  
🐍 Python analytics  
🎓 Academic-ready project  

---

# 👨‍💻 Author

Statistical learning & Python analysis project.

---

