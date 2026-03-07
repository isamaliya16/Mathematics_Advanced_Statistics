# 📊 Statistical Distributions & Transformations

This repository contains detailed theoretical explanations of:

- Log-Normal Distribution
- Power Law Distribution
- Box-Cox Transformation

---

# 📌 Q1. What is a Log-Normal Distribution?

A **Log-Normal distribution** is a probability distribution of a random variable whose **logarithm is normally distributed**.

If:

    Y = log(X)

is normally distributed, then:

    X follows a Log-Normal distribution

### Key Properties:
- Always positive values (X > 0)
- Right-skewed distribution
- Mean > Median > Mode
- Common in financial and economic data

---

# 📌 Q2. Difference Between Normal and Log-Normal Distribution

| Feature | Normal Distribution | Log-Normal Distribution |
|----------|-------------------|--------------------------|
| Shape | Symmetric (Bell Curve) | Right-Skewed |
| Range | (-∞, +∞) | (0, +∞) |
| Negative Values | Possible | Not Possible |
| Mean vs Median | Equal | Mean > Median |

---

# 📌 Q3. Real-Life Examples of Log-Normal Distribution

1. Income distribution  
2. Stock prices and financial returns  

---

# 📌 Q4. What is a Power Law Distribution?

A **Power Law distribution** follows:

    P(x) ∝ x^(-α)

It means probability decreases as a power of x.

### Important Idea:
Small events are common, large events are rare but impactful.

---

# 📌 Q5. Power Law and the 80/20 Rule (Pareto Principle)

The Pareto Principle was introduced by **Vilfredo Pareto**.

It states:
> 80% of results come from 20% of causes.

Examples:
- 80% of wealth owned by 20% of people
- 80% of sales from 20% of customers

Power Law naturally explains this imbalance.

---

# 📌 Q6. Real-World Examples of Power Law

1. Earthquake magnitudes  
2. City population sizes  
3. Social media followers  
4. Word frequency in language  

---

# 📌 Q7. Key Characteristics of Power Law

- Heavy-tailed distribution  
- Scale invariant  
- Few large values dominate  
- Straight line on log-log plot  

---

# 📌 Q8. What is the Box-Cox Transformation?

The **Box-Cox transformation** was introduced by George Box and David Cox.

It transforms non-normal data to make it more normally distributed.

### Formula:

For λ ≠ 0:

    Y(λ) = (X^λ − 1) / λ

For λ = 0:

    Y = log(X)

---

# 📌 Q9. Why Apply Box-Cox Before Modeling?

- Reduce skewness  
- Improve normality  
- Stabilize variance  
- Improve regression model accuracy  

---

# 📌 Q10. Role of Lambda (λ)

Lambda controls the transformation type:

| Lambda | Transformation |
|--------|---------------|
| 1 | No change |
| 0 | Log transform |
| 0.5 | Square root |
| -1 | Reciprocal |

The best λ is chosen to make data closest to normal.

---

# 📌 Q11. How Box-Cox Stabilizes Variance

Box-Cox compresses large values more than small ones.

This:
- Reduces heteroscedasticity  
- Makes variance more constant  
- Improves statistical modeling  

---

# 📌 Q12. Example Scenario

**House Price Prediction**

House prices are right-skewed:
- Many mid-priced houses  
- Few extremely expensive houses  

Applying Box-Cox:
- Reduces skewness  
- Makes data more normal  
- Improves prediction accuracy  

---

# 📚 Summary

| Concept | Purpose |
|----------|---------|
| Log-Normal | Models multiplicative growth |
| Power Law | Explains imbalance (80/20 rule) |
| Box-Cox | Makes data suitable for regression |

---

# 🚀 Applications

- Data Science  
- Machine Learning  
- Financial Analysis  
- Econometrics  
- Predictive Modeling  

---
