# A-B-TESTING-REGRESSION-ANALYSIS


# 📊 Facebook vs YouTube Ad Campaign Analysis

## 🧠 Project Overview

As a marketing agency, our core objective is to **maximize the return on investment (ROI)** for our clients’ advertising efforts. In this project, we analyzed performance data from **two digital advertising campaigns** — one on **Facebook** and the other on **YouTube** — to determine which platform delivers **better results** in terms of:

- 🔁 Clicks  
- ✅ Conversions  
- 💸 Cost-effectiveness  

By identifying the more impactful platform, we aim to **optimize future ad spend**, **streamline targeting**, and **drive better business outcomes**.

---

## 📌 Business Problem

> “We need to determine which advertising platform — Facebook or YouTube — yields a higher ROI by comparing user engagement metrics (clicks and conversions) and cost efficiency. This insight will help us allocate budgets more effectively in future campaigns.”

---

## 📊 Methodology

This project was divided into two major analytical components:

### ✅ 1. A/B Testing using Hypothesis Testing  
We conducted A/B testing to statistically compare Facebook and YouTube ad campaigns using:

- **Null Hypothesis (H₀)**: There is no significant difference between the mean conversions/clicks from Facebook and YouTube ads.
- **Alternative Hypothesis (H₁)**: There is a significant difference between the means.

#### 🧪 Tests Performed:
- **Two-sample t-test** (assuming unequal variance)
- Computed:
  - 📉 **t-statistic**
  - 🧪 **p-value**

#### 📈 Inference:
- The p-value was found to be **less than 0.05**, indicating that we can **reject the null hypothesis**.
- This means there is a **statistically significant difference** between the two platforms.
- Based on the test results, **YouTube showed a higher average in both ad clicks and conversions**.

---

### 🔍 2. Regression Analysis: Predicting YouTube Ad Conversions

After concluding that **YouTube ads perform better**, we used **simple linear regression** to predict the number of conversions based on the number of clicks.

#### 🎯 Objective:
> Given a number of YouTube ad clicks, predict how many conversions can be expected.

#### 🧠 Model:
We used a basic linear regression model where:

- **X (independent variable)**: YouTube ad clicks  
- **Y (dependent variable)**: YouTube ad conversions

#### The model is represented as:
- **Conversions** = β₀ + β₁ × Clicks
#### Where:  
- **β₀** is the intercept  
- **β₁** is the slope of the line (change in conversions per click)

#### 📈 Key Takeaways:
- The regression model showed a **positive linear relationship** between clicks and conversions.
- **R² score** indicated good explanatory power of the model.
- This allowed us to make accurate predictions for conversions from future campaigns.

#### 📌 Example:
If we receive **500 YouTube ad clicks**, and the model outputs:
- **Conversions** = 3 + 0.12 × 500 = 63 conversions


