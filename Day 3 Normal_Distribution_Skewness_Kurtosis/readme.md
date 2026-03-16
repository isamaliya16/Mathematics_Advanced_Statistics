# 📈 Probability Distributions & Data Shape (Advanced Statistics)

---

## 📑 Table of Contents
1. Gaussian (Normal) Distribution
2. Characteristics of Normal Distribution
3. Importance of Normal Distribution
4. Percentiles
5. Quartiles (Q1, Q2, Q3)
6. Interquartile Range (IQR)
7. Five Number Summary
8. Boxplot Representation
9. Boxplot & Outliers
10. Skewness
11. Positive Skewness
12. Negative Skewness
13. Effect of Skewness on Mean, Median, Mode
14. Importance of Handling Skewness
15. Kurtosis
16. Types of Kurtosis
17. Kurtosis & Tails/Outliers
18. Why Kurtosis is Compared with 3

---

## 1️⃣ Gaussian (Normal) Distribution
📌 **Definition:**
A Gaussian distribution is a continuous probability distribution that is symmetric about its mean, forming a bell-shaped curve.

📐 **Formula:**
```
f(x) = (1 / √(2πσ²)) · e^{-(x−μ)² / 2σ²}
```

### 📊 Figure 1: Normal Distribution Curve
```
            /\
          /    \
        /        \
------/---- μ ----\------
```

---

## 2️⃣ Key Characteristics of Normal Distribution

- 🔔 Bell-shaped and symmetric
- 📍 Mean = Median = Mode
- 📐 Defined by μ (mean) and σ (standard deviation)
- 📊 Follows 68–95–99.7 rule

---

## 3️⃣ Importance in Data Analysis & Machine Learning

✨ Why it matters:
- Many real-world variables follow normal distribution
- Basis of statistical tests (z-test, t-test)
- Improves model assumptions in ML
- Helps detect anomalies

---

## 4️⃣ Percentiles

📌 **Definition:**
A percentile indicates the value below which a given percentage of observations fall.

### 📊 Figure 2: Percentile View
```
0% ---- 25% ---- 50% ---- 75% ---- 100%
```

📊 **Use:** Exam scores, salaries, rankings

---

## 5️⃣ Quartiles (Q1, Q2, Q3)

📌 **Definition:**
Quartiles divide data into four equal parts.

- Q1 → 25th percentile
- Q2 → 50th percentile (Median)
- Q3 → 75th percentile

### 📊 Figure 3: Quartiles
```
Min --- Q1 --- Q2 --- Q3 --- Max
```

---

## 6️⃣ Interquartile Range (IQR)

📌 **Definition:**
IQR measures the spread of the middle 50% of data.

📐 **Formula:**
```
IQR = Q3 − Q1
```

📊 **Represents:** Data stability & variability

---

## 7️⃣ Five Number Summary

📌 **Components:**
- Minimum
- Q1 (25%)
- Median (Q2)
- Q3 (75%)
- Maximum

```
[Min | Q1 | Median | Q3 | Max]
```

---

## 8️⃣ Boxplot Representation

📌 A boxplot visually represents the five-number summary.

### 📊 Figure 4: Boxplot
```
Min ──|────[ Q1 | Median | Q3 ]────|── Max
```

---

## 9️⃣ Identifying Outliers Using Boxplot

📌 Outliers are values outside:
```
Q1 − 1.5×IQR   or   Q3 + 1.5×IQR
```

📊 **Visual cue:** Points beyond whiskers

---

## 🔟 Skewness

📌 **Definition:**
Skewness measures the asymmetry of a distribution.

### 📊 Figure 5: Skewness Types
```
Left Skew   Symmetric   Right Skew
```

---

## 1️⃣1️⃣ Positive Skewness

📌 Long tail on the right side.

```
|****
|  ****
|      ******
```

Mean > Median > Mode

---

## 1️⃣2️⃣ Negative Skewness

📌 Long tail on the left side.

```
******
    ****
        **|
```

Mean < Median < Mode

---

## 1️⃣3️⃣ Effect of Skewness on Mean, Median & Mode

| Distribution | Relationship |
|-------------|--------------|
| Symmetric | Mean = Median = Mode |
| Positive Skew | Mean > Median > Mode |
| Negative Skew | Mean < Median < Mode |

---

## 1️⃣4️⃣ Importance of Detecting Skewness

✨ Why fix skewness:
- Improves ML model accuracy
- Ensures valid statistical tests
- Reduces bias

🛠️ Techniques: Log transform, Box-Cox, normalization

---

## 1️⃣5️⃣ Kurtosis

📌 **Definition:**
Kurtosis measures the tailedness or peakness of a distribution.

---

## 1️⃣6️⃣ Types of Kurtosis

| Type | Shape | Meaning |
|----|------|--------|
| Leptokurtic | Sharp peak | More outliers |
| Mesokurtic | Normal | Balanced |
| Platykurtic | Flat | Fewer outliers |

---

## 1️⃣7️⃣ Kurtosis & Tails/Outliers

📌 Higher kurtosis → heavier tails → more extreme values

```
Flat    Normal    Sharp
```

---

## 1️⃣8️⃣ Why Kurtosis is Compared with 3

📌 Normal distribution has kurtosis = 3

- > 3 → Leptokurtic
- = 3 → Mesokurtic
- < 3 → Platykurtic

---
