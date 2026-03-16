# 📊 Probability Functions in Statistics
### PMF • PDF • CDF — Concepts, Use Cases & Real-World Examples

---

## 📌 Overview
In statistics and data science, **probability functions** describe the likelihood of different outcomes for a random variable.  
The three most important probability functions are:

- **PMF** – Probability Mass Function  
- **PDF** – Probability Density Function  
- **CDF** – Cumulative Distribution Function  

Understanding **when and how to use each** is essential for:
- Data analysis
- Machine learning
- Risk assessment
- Real-world decision making

---

## 🎯 Objectives
This project aims to:
- Explain **PMF, PDF, and CDF** clearly
- Identify **when each function is used**
- Provide **real-time practical examples**
- Help beginners build a **strong statistical foundation**

---

## 🧠 Key Concepts

### 🔹 Random Variable
A **random variable** represents outcomes of a random process.

- **Discrete Random Variable** → Countable values  
- **Continuous Random Variable** → Infinite possible values  

---

## 1️⃣ Probability Mass Function (PMF)

### 📖 Definition
A **Probability Mass Function (PMF)** gives the probability that a **discrete random variable** takes an **exact value**.

\[
PMF(x) = P(X = x)
\]

### 📌 When to Use PMF
Use PMF **only when the data is discrete** (countable).

✅ Suitable for:
- Integers
- Finite outcomes
- Count-based data

❌ Not suitable for continuous values

### 🌍 Real-World Example
**E-commerce Orders per Hour**

| Orders (X) | Probability |
|----------|-------------|
| 0 | 0.10 |
| 1 | 0.20 |
| 2 | 0.35 |
| 3 | 0.25 |
| 4 | 0.10 |

> The probability of receiving exactly 2 orders in an hour is **0.35**

---

## 2️⃣ Probability Density Function (PDF)

### 📖 Definition
A **Probability Density Function (PDF)** describes the **density of probability** for a **continuous random variable**.

⚠️ Important:
\[
P(X = x) = 0
\]

Probability is calculated over an **interval**, not at a single point.

### 📌 When to Use PDF
Use PDF when:
- Data is continuous
- Values are measurable with infinite precision

### 🌍 Real-World Example
**Delivery Time of Packages**

- Mean delivery time = 5 days  
- Standard deviation = 1 day  

> Probability that delivery time lies between **4 and 6 days** is calculated using PDF (area under the curve).

---

## 3️⃣ Cumulative Distribution Function (CDF)

### 📖 Definition
The **Cumulative Distribution Function (CDF)** gives the probability that a random variable is **less than or equal to a value**.

\[
CDF(x) = P(X \le x)
\]

### 📌 When to Use CDF
Use CDF when you want:
- Probability up to a threshold
- Percentile calculations
- Risk analysis

### 🌍 Real-World Example
**Customer Waiting Time**

> What is the probability a customer waits **less than 10 minutes**?  
This is answered using **CDF**.

---

## 🏭 Industry Use Cases

### 🏦 Banking & Finance
- PMF → Number of missed EMIs  
- PDF → Income distribution  
- CDF → Credit risk thresholds  

### 📦 E-Commerce
- PMF → Product returns count  
- PDF → Delivery time analysis  
- CDF → Probability of fast delivery  

### 🏥 Healthcare
- PMF → Number of patient visits  
- PDF → Blood pressure distribution  
- CDF → Probability BP below danger level  

### 🤖 Data Science & ML
- Feature distribution analysis  
- Outlier detection  
- Probabilistic modeling  

---

## 📊 Comparison Table

| Function | Data Type | Used For | Output |
|--------|----------|---------|-------|
| PMF | Discrete | Exact probability | P(X = x) |
| PDF | Continuous | Probability density | Area under curve |
| CDF | Both | Cumulative probability | P(X ≤ x) |

---

## 🧠 Memory Trick
- **PMF** → *Mass* → Countable  
- **PDF** → *Density* → Continuous  
- **CDF** → *Cumulative* → Up to X  

--- 

## Histogram `density` Parameter in Matplotlib

The `density` parameter in `plt.hist()` controls how the histogram is scaled.

### `density=False` (default) 
- The histogram shows the **count of values** in each bin.
- The y-axis represents **frequency** (number of occurrences).
 
### `density=True`
- The histogram shows a **probability density**.
- The **area under the histogram sums to 1**.
- Useful when comparing your data to a **probability distribution** (e.g., Normal distribution).

---
