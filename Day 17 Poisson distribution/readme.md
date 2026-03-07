# 📊 Probability & Statistics – 

- Poisson Distribution  
- Z-Score  
- Probability Density Function (PDF)  
- Cumulative Distribution Function (CDF)  

---

# ✅ Q.1 What is a Poisson Distribution?

A **Poisson distribution** is a discrete probability distribution that describes the number of events occurring in a fixed interval of time, space, or area, provided:

- Events occur independently.
- The average rate (λ) remains constant.
- Two events cannot occur at the exact same instant.

It is mainly used for **count data**.

### 📌 Formula: P(X = k) = (e^(-λ) × λ^k) / k!

Where:
- λ = average number of events
- k = number of occurrences
- e ≈ 2.718
- k! = factorial of k

---

# ✅ Q.2 Two Conditions for Poisson Distribution

1. Events occur independently.  
2. The average rate (λ) is constant over time or space.

---

# ✅ Q.3 Mean and Variance of Poisson Distribution

For a Poisson distribution:

- Mean (μ) = λ  
- Variance (σ²) = λ  

👉 Important Property: Mean = Variance = λ

---

# ✅ Q.4 Real-Life Example of Poisson Distribution

Example:

📞 Number of customer calls received per minute in a call center.

If the average calls per minute = 5, we can calculate:

- Probability of exactly 3 calls
- Probability of more than 7 calls
- Probability of zero calls

Other examples:
- Number of accidents per day
- Number of website visitors per hour
- Number of defects in manufacturing

---

# 📈 Z-SCORE

# ✅ Q.5 What is a Z-Score?

A **Z-score** measures how many standard deviations a value is from the mean.

### 📌 Formula:
Z = (X − μ) / σ

Where:
- X = data value  
- μ = mean  
- σ = standard deviation  

---

# ✅ Q.6 How Z-Score Helps in Comparing Data?

Z-score converts data into a standard scale:

- Mean = 0  
- Standard deviation = 1  

This allows comparison between different datasets even if their units are different.

Example:
Two students scored differently in two subjects with different averages. Z-score helps determine who performed better relative to their group.

---

# ✅ Q.7 Positive and Negative Z-Score Meaning

- Z > 0 → Value is above the mean  
- Z < 0 → Value is below the mean  
- Z = 0 → Value equals the mean  

Higher absolute Z-value → farther from the mean.

---

# 📉 PROBABILITY DENSITY FUNCTION (PDF)

# ✅ Q.8 What is PDF?

A **Probability Density Function (PDF)** describes the likelihood of a continuous random variable.

Important Points:

- Used for continuous data
- Probability at a single point = 0
- Probability is calculated over an interval

Example:
Height, weight, temperature.

---

# ✅ Q.9 What Does Area Under PDF Represent?

The area under the PDF curve represents probability.

- Total area under curve = 1  
- Area between two points = Probability that value lies in that interval  
P(a < X < b)

---

# 📊 CUMULATIVE DISTRIBUTION FUNCTION (CDF)

# ✅ Q.10 Define CDF

The **Cumulative Distribution Function (CDF)** gives: 
F(x) = P(X ≤ x)

It represents the probability that the random variable is less than or equal to a given value.

---

# ✅ Q.11 Relationship Between PDF and CDF

CDF is the integral of PDF:
F(x) = ∫[−∞ to x] f(t) dt  

PDF is the derivative of CDF:
f(x) = d/dx [F(x)]  

---

# ✅ Q.12 Example of CDF in Decision-Making

Example:

In an exam, passing marks = 40.

Using CDF:
P(X ≤ 40)

We can find:
- Percentage of students who failed.
- Overall pass rate.

Business Example:

In quality control:
- If product weight follows a distribution,
- CDF helps calculate probability of defective products.
- Helps in production decisions.

--- 

# 🎯 Summary Table

| Concept | Key Idea |
|----------|----------|
| Poisson Distribution | Models count of events |
| Mean & Variance | Both equal λ |
| Z-Score | Distance from mean in standard units |
| PDF | Density of continuous variable |
| CDF | Cumulative probability |
| PDF & CDF | CDF = Integral of PDF |

---

