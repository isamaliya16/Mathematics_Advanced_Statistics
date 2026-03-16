# 📊 Z-Test: One-Sample and Two-Sample Hypothesis Testing

## 📌 Overview

This document provides a clear and professional explanation of:

- One-Sample Z-Test
- Two-Sample Z-Test
- Assumptions
- Mathematical Formulas
- Hypothesis Structure
- Decision Rules

Z-tests are widely used in statistics, data science, research, and quality control when the population standard deviation is known.

---

# 🧪 1️⃣ One-Sample Z-Test

## 🔹 Definition

A **One-Sample Z-Test** is used to determine whether the mean of a sample differs significantly from a known or assumed population mean when the population standard deviation (σ) is known.

---

## 🔹 When to Use

Use a One-Sample Z-Test when:

- Population standard deviation (σ) is known
- Sample size is large (n ≥ 30)
- Data is approximately normally distributed
- Observations are independent

---

## 🔹 Hypotheses

- **Null Hypothesis (H₀):**
  
  μ = μ₀  

- **Alternative Hypothesis (H₁):**

  - Two-tailed: μ ≠ μ₀  
  - Right-tailed: μ > μ₀  
  - Left-tailed: μ < μ₀  

Where:  
μ₀ = Claimed population mean

---

## 🔹 Z-Statistic Formula (One-Sample)

The test statistic is calculated as:

Z = (X̄ − μ₀) / (σ / √n)

Where:

- X̄ = Sample mean  
- μ₀ = Population mean (claimed value)  
- σ = Population standard deviation  
- n = Sample size  
- √n = Square root of sample size  

---

## 🔹 Interpretation

1. Calculate the Z value.
2. Compare with critical value from Z-table.
3. Or compute the p-value.

### Decision Rule

- If |Z| > Zcritical → Reject H₀  
- If |Z| ≤ Zcritical → Fail to reject H₀  

Or

- If p-value ≤ α → Reject H₀  
- If p-value > α → Fail to reject H₀  

(α = Significance level, typically 0.05)

---

# 🧪 2️⃣ Two-Sample Z-Test

## 🔹 Definition

A **Two-Sample Z-Test** is used to determine whether the means of two independent populations are significantly different when both population standard deviations are known.

---

## 🔹 When to Use

- Two independent samples
- Population standard deviations are known
- Large sample sizes
- Data approximately normal

---

## 🔹 Hypotheses

- **Null Hypothesis (H₀):**

  μ₁ = μ₂  
  or  
  μ₁ − μ₂ = 0  

- **Alternative Hypothesis (H₁):**

  - Two-tailed: μ₁ ≠ μ₂  
  - Right-tailed: μ₁ > μ₂  
  - Left-tailed: μ₁ < μ₂  

---

## 🔹 Z-Statistic Formula (Two-Sample)

Z = (X̄₁ − X̄₂) / √[(σ₁² / n₁) + (σ₂² / n₂)]

Where:

- X̄₁ = Mean of sample 1  
- X̄₂ = Mean of sample 2  
- σ₁ = Population standard deviation of group 1  
- σ₂ = Population standard deviation of group 2  
- n₁ = Sample size of group 1  
- n₂ = Sample size of group 2  

---

## 🔹 Interpretation

1. Compute the Z value.
2. Compare with Z critical value.
3. Or compute the p-value.

### Decision Rule

- If |Z| > Zcritical → Reject H₀  
- If |Z| ≤ Zcritical → Fail to reject H₀  

---

# 📊 Key Differences

| Feature | One-Sample Z-Test | Two-Sample Z-Test |
|----------|------------------|------------------|
| Purpose | Compare sample mean with population mean | Compare two population means |
| Samples | One | Two |
| σ Known | Yes | Yes |
| Formula | Uses single standard error | Uses combined standard error |

---

# 📌 Assumptions Summary

- Random sampling
- Independent observations
- Known population standard deviation
- Normal distribution or large sample size

---

# 📚 Applications

- Quality control in manufacturing
- Business performance analysis
- Medical research trials
- Customer behavior studies
- Industrial testing

---

# 🎯 Conclusion

Z-tests are powerful statistical tools for testing hypotheses about population means when the population variance is known. They provide a structured and reliable method for making data-driven decisions.

---

### 👨‍💻 Author
Ayush Isamaliya
