# 🎵 Spotify User Behavior & Premium Conversion Analysis

## 📌 Project Overview

This project analyzes Spotify user behavior to identify the factors that influence premium subscription conversion. The analysis combines SQL, Python, statistical hypothesis testing, and Power BI to generate business insights and build an interactive dashboard.

---

## 🎯 Business Problem

Spotify wants to understand:

- Which users are more likely to subscribe to Premium?
- Does user engagement influence Premium conversion?
- Do advertisements significantly improve conversion?
- Which user behaviors are most closely related to Premium subscriptions?

---

## 🛠️ Tools Used

- PostgreSQL
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Power BI

---

## 📊 Project Workflow

### 1. Data Cleaning

- Checked missing values
- Checked duplicate records
- Created new analytical columns:
  - premium
  - churn
  - is_high_engagement

---

### 2. SQL Analysis

Business questions answered using PostgreSQL:

- Subscription distribution
- User demographics
- Listening behaviour
- Device usage
- Churn analysis
- Premium conversion analysis

---

### 3. Python Analysis

Performed Exploratory Data Analysis (EDA):

- Subscription Distribution
- Listening Hours Distribution
- Engagement Analysis
- Correlation Heatmap
- A/B Testing

---

### 4. Statistical Testing

Performed a Two-Proportion Z-Test.

**Hypothesis**

H₀: Ad interaction does not affect Premium conversion.

H₁: Ad interaction affects Premium conversion.

Result:

- Z-statistic = -1.765
- P-value = 0.0776

Conclusion:

The result was **not statistically significant**, indicating that ad interaction alone does not significantly influence Premium conversion.

---

### 5. Power BI Dashboard

Interactive dashboard includes:

- Executive Overview
- User Engagement Analysis
- Subscription Analysis
- A/B Testing Insights

---

## 📈 Key Insights

- Nearly half of users subscribe to Premium plans.
- High engagement users do not convert significantly more than low engagement users.
- Advertisement exposure showed only a slight increase in Premium conversion.
- No statistically significant evidence was found that advertisements alone drive subscriptions.

---

## 🚀 Future Improvements

- Connect Power BI directly to PostgreSQL
- Build a Premium prediction model using Machine Learning
- Deploy dashboard to Power BI Service

---

## 👩‍💻 Author

Sanjana K

Master's in Big Data Management & Analytics

Aspiring Data Analyst
