# 📊 t-Test Fundamentals — README

This guide explains the first five foundational questions about the **t-test**, including definitions, assumptions, formulas, and a worked example.

---

## ✅ Q1 — What is a one-sample t-test?

A **one-sample t-test** is a statistical method used to determine whether the mean of a sample is significantly different from a known or hypothesized population mean.

It is used when:

- Population standard deviation is **unknown**
- Sample size is **small**
- Data is approximately **normally distributed**

---

## ✅ Q2 — When should you use a t-test instead of a z-test?

Use a **t-test** instead of a **z-test** when:

- Population standard deviation (σ) is **unknown**
- Sample size is **small** (typically n < 30)
- You estimate variability using the **sample standard deviation**

Use a **z-test** only when σ is known and/or the sample size is large.

---

## ✅ Q3 — Assumptions of a one-sample t-test

For valid results, the following assumptions must hold:

1. The sample is **randomly selected**
2. Observations are **independent**
3. The data is approximately **normally distributed**
4. Measurement scale is **continuous**

---

## ✅ Q4 — Formula for the one-sample t-statistic

The t-statistic is calculated as:

t = (x̄ − μ) / (s / √n)

Where:
- x̄ = sample mean  
- μ = population mean  
- s = sample standard deviation  
- n = sample size  

Degrees of freedom: df = n − 1

---

## ✅ Q5 — One-Sample t-Test Worked Example

### 📘 Problem

A class claims its average test score is **75**.

A random sample of **10 students** shows:

- Sample mean (x̄) = 70  
- Sample standard deviation (s) = 8  

Test whether the class claim is valid at **α = 0.05**.

---

### 🔍 Step 1 — State the Hypotheses

Null hypothesis (H₀):  
μ = 75  (The class average score is 75)

Alternative hypothesis (H₁):  
μ ≠ 75  (The class average score is different from 75)

This is a **two-tailed test**.

---

### 📐 Step 2 — Formula

t = (x̄ − μ) / (s / √n)

---

### 🧮 Step 3 — Calculate the t-Statistic

t = (70 − 75) / (8 / √10)

t = −5 / 2.53

t ≈ −1.98

---

### 📊 Step 4 — Degrees of Freedom

df = n − 1  
df = 10 − 1 = 9

Critical t-value (α = 0.05, two-tailed, df = 9):

t₍critical₎ ≈ ±2.262

---

### ✅ Step 5 — Decision Rule

|t| = 1.98  
1.98 < 2.262

Fail to reject H₀

---

### 🎯 Conclusion
There is **not enough statistical evidence** to reject the claim that the class average score is 75.

The observed difference could be due to sampling variation.

---

## ✅ Q6 — Role of Degrees of Freedom in a One-Sample t-Test

### 📘 Explanation

**Degrees of freedom (df)** represent the number of independent values that can vary in a statistical calculation.

For a one-sample t-test:

df = n − 1

Degrees of freedom affect:

- The **shape** of the t-distribution
- The **critical t-value**
- The **accuracy** of inference

As sample size increases, the t-distribution becomes closer to the normal distribution.

---

## ✅ Q7 — Effect of Sample Size on a One-Sample t-Test

### 📘 Explanation

Sample size plays a critical role in hypothesis testing:

- Larger samples produce **more reliable estimates**
- Standard error decreases as sample size increases
- Test results become **more precise**
- Statistical power increases

Small samples lead to greater uncertainty, which is why the t-distribution accounts for sample size.

---

## ✅ Q8 — What is a Two-Sample t-Test?

### 📘 Explanation

A **two-sample t-test** compares the means of two independent groups to determine whether their population means are significantly different.

It is used when:

- Comparing two groups
- Population variances are unknown
- Samples are independent

Example applications include comparing treatment effects or performance between groups.

---

## ✅ Q9 — Independent vs Paired Two-Sample t-Tests

### 📘 Independent t-Test

Used when:

- Groups are unrelated
- Observations come from different subjects

Example: Comparing scores of two different classes.

---

### 📘 Paired t-Test

Used when:

- Observations are related or matched
- Measurements come from the same subjects

Example: Before-and-after treatment comparison.

---

### 🔑 Key Difference

Independent → separate groups  
Paired → same or matched subjects

---

## ✅ Q10 — Assumptions of a Two-Sample t-Test

For valid results, these assumptions must hold:

1. Samples are **randomly selected**
2. Observations are **independent**
3. Data in each group is approximately **normally distributed**
4. Variances are equal (for pooled t-test)
5. Measurement scale is **continuous**

If equal variance is not assumed, Welch’s t-test is used instead.

---
## ✅ Q11 — Formula for Independent Two-Sample t-Test

### 📘 Explanation

The independent two-sample t-test compares the means of two unrelated groups.

### 📐 Formula (Pooled Variance Case)

t = (x̄₁ − x̄₂) / √[ Sp²(1/n₁ + 1/n₂) ]

Where:

x̄₁, x̄₂ = sample means  
n₁, n₂ = sample sizes  
Sp² = pooled variance  

Pooled variance:

Sp² = [ (n₁−1)s₁² + (n₂−1)s₂² ] / (n₁+n₂−2)

Degrees of freedom:

df = n₁ + n₂ − 2

---

## ✅ Q12 — Two-Sample t-Test Worked Procedure

### 📘 Problem

Two groups of patients receive different medicines. Their recovery times are recorded. We want to test if the medicines produce significantly different average recovery times.

---

### 🔍 Step-by-Step Procedure

**Step 1 — Hypotheses**

H₀: μ₁ = μ₂  
(No difference in recovery times)

H₁: μ₁ ≠ μ₂  
(Recovery times differ)

---

**Step 2 — Choose significance level**

α = 0.05 (commonly used)

---

**Step 3 — Compute test statistic**

t = (x̄₁ − x̄₂) / √[ Sp²(1/n₁ + 1/n₂) ]

---

**Step 4 — Find critical value**

Use t-table with df = n₁ + n₂ − 2

---

**Step 5 — Decision**

Reject H₀ if |t| > t₍critical₎

---

**Conclusion**

Interpret results in context of recovery effectiveness.

---

## ✅ Q13 — Hypotheses in a Two-Sample t-Test

### 📘 Explanation

Hypotheses compare population means of two groups.

Null hypothesis:

H₀: μ₁ = μ₂  
(No significant difference)

Alternative hypotheses:

Two-tailed → H₁: μ₁ ≠ μ₂  
Right-tailed → H₁: μ₁ > μ₂  
Left-tailed → H₁: μ₁ < μ₂

Choice depends on research question.

---

## ✅ Q14 — When to Use a Pooled Variance t-Test

### 📘 Explanation

A pooled variance t-test is used when:

- Population variances are **assumed equal**
- Sample sizes are reasonable
- Groups are independent

Benefits:

- Provides a combined estimate of variability
- Improves statistical efficiency

If variances differ significantly → use **Welch’s t-test** instead.

---

## ✅ Q15 — Meaning of p-value < 0.05 in a Two-Sample t-Test

### 📘 Explanation

A p-value represents the probability of observing results as extreme as the sample data, assuming H₀ is true.

If:

p-value < 0.05

Then:

- Evidence against H₀ is strong
- Reject the null hypothesis
- The difference between group means is statistically significant

---
