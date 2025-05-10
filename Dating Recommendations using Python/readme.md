# Dating Recommendations using Python

This project applies **Recency-Frequency-Monetary (RFM) analysis** to a dating application dataset to generate meaningful user segments and provide tailored recommendations based on user behavior patterns.

## 📁 Dataset Description

The dataset `dating_app_dataset.csv` contains user behavior and demographic data from a dating app. The key features include:

- **UserID**: Unique identifier for each user.
- **Gender**: Gender of the user (e.g., Male, Female).
- **Age**: Age of the user.
- **Education Level**: Educational qualification.
- **App Usage Frequency**: Number of app interactions within a timeframe.
- **Last Active Date**: The last time the user accessed the app.
- **Total Spend**: Amount spent by the user on premium services or features.

This dataset is used to understand engagement trends, identify user clusters, and tailor personalized strategies using RFM analysis.

---

## 📊 Exploratory Data Analysis

### Age Distribution by Gender

![Age Distribution by Gender](https://github.com/MohithKumar8897/Recency-Frequency-Monetary-RFM-analysis/raw/main/Dating%20Recommendations%20using%20Python/Age%20Distribution%20by%20gender.png)

This plot visualizes age patterns across different genders in the user base.

---

### Education Level Distribution by Gender

![Education Level Distribution by Gender](https://github.com/MohithKumar8897/Recency-Frequency-Monetary-RFM-analysis/raw/main/Dating%20Recommendations%20using%20Python/Education%20Level%20Distribution%20by%20Gender.png)

This chart displays the educational background of users segmented by gender.

---

### Frequency of App Usage

![Frequency of App Usage](https://github.com/MohithKumar8897/Recency-Frequency-Monetary-RFM-analysis/raw/main/Dating%20Recommendations%20using%20Python/Frequency%20of%20App%20Usage%20Distribution%20.png)

Shows the distribution of how frequently users interact with the app.

---

## 🧠 RFM Analysis

RFM analysis segments users based on:

- **Recency (R)**: Days since last activity.
- **Frequency (F)**: Number of visits/interactions.
- **Monetary (M)**: Total amount spent.

This approach identifies the following types of users:

- **Champions**: Recent, frequent, high spenders.
- **Loyal**: Frequent users with consistent engagement.
- **At-Risk**: High spenders not active recently.
- **New**: Recent signups with low usage.

These insights guide marketing efforts and feature prioritization.

---

## 💡 Recommendations

Based on RFM segmentation:

- **Champions**: Reward with exclusive features or loyalty bonuses.
- **Loyal**: Encourage spending via targeted offers.
- **At-Risk**: Re-engagement campaigns via notifications or discounts.
- **New**: Welcome onboarding, offer first-time bonuses.

---
