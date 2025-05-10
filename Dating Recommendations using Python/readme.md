# 💘 Dating Recommendations using Python

This project applies **Recency-Frequency-Monetary (RFM) analysis** to a dating app dataset to identify user behavior patterns and generate personalized engagement strategies.

---

## 📁 Dataset Description

The dataset `dating_app_dataset.csv` contains user behavior and demographic data from a dating app. Key features include:

- **User ID**: A unique identifier for each user.
- **Age**: The age of the user.
- **Gender**: The gender of the user (e.g., Male, Female).
- **Height**: The height of the user.
- **Interests**: A list of interests or hobbies.
- **Looking For**: Dating preferences (e.g., Long-term Relationship, Marriage).
- **Children**: Whether the user has children (“Yes,” “No,” “Maybe”).
- **Education Level**: Highest education attained.
- **Occupation**: The user’s current occupation.
- **Swiping History**: A numerical score based on user interactions (likes/dislikes).
- **Frequency of Usage**: App engagement frequency (e.g., Daily, Monthly).
- **App Usage Frequency**: Total number of app interactions in a given timeframe.
- **Last Active Date**: Most recent login or activity date.
- **Total Spend**: Amount spent on premium features or services.

This dataset is used to understand engagement, cluster users, and make targeted recommendations.

---

## 📊 Exploratory Data Analysis

### 1. Age Distribution by Gender  
Visualizes how age is distributed among male and female users.  
![Age Distribution by Gender](https://github.com/MohithKumar8897/Recency-Frequency-Monetary-RFM-analysis/raw/main/Dating%20Recommendations%20using%20Python/Age%20Distribution%20by%20gender.png)

### 2. Education Level by Gender  
Shows the educational background of users segmented by gender.  
![Education Level Distribution by Gender](https://github.com/MohithKumar8897/Recency-Frequency-Monetary-RFM-analysis/raw/main/Dating%20Recommendations%20using%20Python/Education%20Level%20Distribution%20by%20Gender.png)

### 3. Frequency of App Usage  
Displays how frequently users interact with the app.  
![Frequency of App Usage](https://github.com/MohithKumar8897/Recency-Frequency-Monetary-RFM-analysis/raw/main/Dating%20Recommendations%20using%20Python/Frequency%20of%20App%20Usage%20Distribution%20.png)

---

## 🧠 RFM Analysis

RFM segments users based on:

- **Recency (R)**: How recently a user was active.
- **Frequency (F)**: How often they use the app.
- **Monetary (M)**: How much they've spent.

### User Segments Identified:

- **Champions**: Active recently, frequent usage, high spenders.
- **Loyal**: Frequent users with stable engagement.
- **At-Risk**: Users who spent a lot but haven’t been active lately.
- **New**: Recently joined, minimal usage.

---

## 💡 Recommendations

Based on RFM categories:

- **Champions**: Provide loyalty bonuses or VIP features.
- **Loyal**: Encourage upsell with exclusive offers.
- **At-Risk**: Trigger re-engagement via push notifications or email campaigns.
- **New**: Onboard with first-time offers or gamified tutorials.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Data visualization
- **Datetime** – Recency calculation

---
