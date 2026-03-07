# 📊 Spread Locator  
## 🔍 A Statistical Distribution Analysis Model  

> 🎯 Understanding Data Spread, Skewness & Probability Behavior in E-Commerce Transactions  
> 🧠 Distribution Modeling | Q-Q Plot | Box-Cox | Z-Score | PDF & CDF  
> 💻 Python-Based Statistical Analysis Project  

---

## 📌 Project Overview  

**Spread Locator** is a statistical distribution analysis model designed to study and interpret the spread behavior of e-commerce transaction data.

This project focuses on:

- 📈 Identifying the best-fitting probability distribution  
- 📊 Understanding skewness and variance  
- 📦 Stabilizing skewed data using transformation techniques  
- 🎯 Deriving probability-based business insights  

---

## 🎯 Objective  

To help students understand and apply:

- Statistical Distributions  
- Q-Q Plot Analysis  
- Discrete & Continuous Modeling  
- Log-Normal & Power-Law Distributions  
- Box-Cox Transformation  
- Z-Score Probability  
- PDF & CDF Interpretation  

---

# 🏢 Business Scenario  

You are working as a Data Analyst for an e-commerce company.

Management wants to:

- Analyze transaction behavior  
- Detect high-value customers  
- Understand transaction frequency  
- Identify distribution patterns  

Your task is to apply statistical distribution modeling and transformation techniques to derive actionable insights.

---

# 📂 Dataset Structure  

| Field Name | Data Type | Description |
|------------|-----------|-------------|
| transaction_id | UUID/String | Unique transaction ID |
| customer_id | UUID/String | Unique customer ID |
| transaction_amount | Float | Transaction value (₹) |
| transaction_date | Date | Date of transaction |
| transaction_count | Int | Weekly transaction count |
| region | String | North / South / East / West |
| transaction_status | String | Success / Fail |

---

# 🧠 Part A - Theoretical Foundation  

## 1️⃣ What is Statistical Distribution?  
A statistical distribution describes how data values are spread across possible outcomes.

---

## 2️⃣ What is a Q-Q Plot?  
A Quantile-Quantile plot compares sample quantiles with theoretical quantiles to test distribution fit.

✔ Straight line → Good fit  
✔ Curved pattern → Skewed distribution  

---

## 3️⃣ Discrete vs Continuous Distributions  

| Discrete | Continuous |
|----------|------------|
| Countable values | Infinite measurable values |
| Example: Transaction count | Example: Transaction amount |

---

## 4️⃣ Bernoulli Distribution  
Used for binary outcomes like transaction success (1) or failure (0).

---

## 5️⃣ Binomial Distribution  
Models number of successes in fixed number of trials.

Example: Weekly successful transactions.

---

## 6️⃣ Poisson Distribution  
Models number of events in a fixed time interval.

Example: Daily transactions on platform.

---

## 7️⃣ Log-Normal Distribution  
If log(X) is normally distributed, then X follows a Log-Normal distribution.

Common in revenue and financial data.

---

## 8️⃣ Power Law Distribution  
Heavy-tailed distribution where extreme values occur more frequently.

---

## 9️⃣ Box-Cox Transformation  
Used to reduce skewness and stabilize variance.

---

## 🔟 Z-Score Probability  

Formula:

Z = (X - μ) / σ

Used to measure how far a value is from the mean.

---

## 1️⃣1️⃣ PDF vs CDF  

| PDF | CDF |
|-----|-----|
| Probability Density Function | Cumulative Distribution Function |
| Shows likelihood at specific value | Shows cumulative probability |

---

# 📊 Part B - Data Analysis & Testing  

## 🛠 Libraries Used  

```python
NumPy
Pandas
SciPy
Statsmodels
Matplotlib
Seaborn
```
---

# 📊 Part B – Detailed Tasks Performed

## ✅ 1. Fit Bernoulli & Binomial Distribution

### 🔹 Bernoulli Distribution
- Modeled transaction status (Success = 1, Fail = 0)
- Estimated probability of success (p)
- Evaluated transaction reliability rate

### 🔹 Binomial Distribution
- Modeled weekly transaction count per customer
- Analyzed number of successful transactions in fixed trials
- Compared theoretical vs actual probabilities

📌 **Business Insight:** 
Helps measure platform performance and weekly customer engagement.

---

## ✅ 2. Fit Poisson Distribution

- Modeled number of daily transactions
- Estimated λ (lambda) parameter:
  
  λ = Average number of transactions per day

- Compared observed vs theoretical Poisson probabilities

📌 Business Insight:
Useful for predicting platform load and traffic spikes.

---

## ✅ 3. Model Log-Normal & Power-Law Distribution

### 🔹 Log-Normal Model
- Fitted transaction_amount
- Checked right-skewed behavior
- Evaluated distribution fit visually and statistically

### 🔹 Power-Law Model
- Tested heavy-tail behavior
- Analyzed presence of extreme high-value transactions

📌 Business Insight:
Identifies whether revenue depends on a few premium customers.

---

## ✅ 4. Generate Q-Q Plot

- Compared sample quantiles with normal distribution quantiles
- Tested normality assumption
- Identified skewness and tail deviations

✔ Straight line → Data follows Normal distribution  
✔ Curvature → Skewed or heavy-tailed distribution  

📌 Business Insight:
Helps decide whether transformation is required.

---

## ✅ 5. Apply Box-Cox Transformation

- Applied Box-Cox transformation on transaction_amount
- Reduced skewness
- Stabilized variance
- Compared before vs after distribution plots

📌 Business Insight:
Improves model performance and statistical reliability.

---

## ✅ 6. Calculate Z-Score

Formula used:

Z = (X - μ) / σ

- Computed Z-score for each transaction
- Calculated probability of transactions exceeding ₹5000
- Identified statistically extreme spenders

📌 Business Insight:
Helps detect VIP customers or unusual spending behavior.

---

## ✅ 7. Plot PDF & CDF

### 🔹 Probability Density Function (PDF)
- Visualized likelihood of transaction amounts
- Checked distribution shape

### 🔹 Cumulative Distribution Function (CDF)
- Calculated cumulative probability
- Estimated probability of transactions below/above threshold

📌 Business Insight:
Provides probability-based decision support.

---

## ✅ 8. Final Conclusion

- Compared all distribution models
- Identified best-fitting distribution
- Justified model selection using visual & statistical evidence
- Provided business recommendations

---

# 📈 Expected Outputs

The project generates the following visualizations:

✔ Histogram of transaction amounts  
✔ Q-Q Plot for normality testing  
✔ Box-Cox transformation comparison  
✔ Log-Normal & Power-Law comparison chart  
✔ PDF curve visualization  
✔ CDF curve visualization  
✔ Poisson probability distribution plot  
✔ Clear interpretation below each chart  

---


# 👨‍💻 Author

**Ayush Isamaliya**  
Aspiring Data Scientist | AI & Machine Learning Enthusiast  

📊 Passionate about Data Analytics, Machine Learning & Statistical Modeling  
🚀 Building real-world projects to solve business problems using data  

---