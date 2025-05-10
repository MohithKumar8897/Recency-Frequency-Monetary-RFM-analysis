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

## Match Recommendations

Here are some sample matchmaking recommendations:

### Recommendation 1:
- **Male Profile (User 36)**:  
  Age: 19  
  Interests: ['Movies', 'Cooking', 'Hiking', 'Reading', 'Sports', 'Travel', 'Music']
  
- **Female Profile (User 451)**:  
  Age: 19  
  Interests: ['Reading', 'Music', 'Cooking', 'Hiking', 'Travel', 'Sports', 'Movies']
  
- **Match Score**: 18.79

---

### Recommendation 2:
- **Male Profile (User 274)**:  
  Age: 29  
  Interests: ['Reading', 'Movies', 'Travel', 'Music', 'Hiking', 'Cooking', 'Sports']
  
- **Female Profile (User 300)**:  
  Age: 29  
  Interests: ['Cooking', 'Reading', 'Music', 'Hiking', 'Travel', 'Sports', 'Movies']
  
- **Match Score**: 18.73

---

### Recommendation 3:
- **Male Profile (User 456)**:  
  Age: 29  
  Interests: ['Cooking', 'Hiking', 'Sports', 'Travel', 'Music', 'Movies', 'Reading']
  
- **Female Profile (User 65)**:  
  Age: 29  
  Interests: ['Travel', 'Movies', 'Reading', 'Sports', 'Music', 'Cooking', 'Hiking']
  
- **Match Score**: 18.69

---

### Recommendation 4:
- **Male Profile (User 147)**:  
  Age: 34  
  Interests: ['Reading', 'Travel', 'Movies', 'Hiking', 'Cooking', 'Music', 'Sports']
  
- **Female Profile (User 287)**:  
  Age: 34  
  Interests: ['Reading', 'Hiking', 'Cooking', 'Music', 'Movies', 'Travel', 'Sports']
  
- **Match Score**: 18.66

---

### Recommendation 5:
- **Male Profile (User 321)**:  
  Age: 20  
  Interests: ['Sports', 'Reading', 'Cooking', 'Travel', 'Movies', 'Hiking', 'Music']
  
- **Female Profile (User 168)**:  
  Age: 20  
  Interests: ['Cooking', 'Sports', 'Music', 'Reading', 'Travel', 'Hiking', 'Movies']
  
- **Match Score**: 18.58

---

### Recommendation 6:
- **Male Profile (User 323)**:  
  Age: 30  
  Interests: ['Hiking', 'Travel', 'Movies', 'Reading', 'Sports', 'Cooking', 'Music']
  
- **Female Profile (User 497)**:  
  Age: 30  
  Interests: ['Hiking', 'Reading', 'Travel', 'Sports', 'Music', 'Cooking', 'Movies']
  
- **Match Score**: 18.57

---

### Recommendation 7:
- **Male Profile (User 181)**:  
  Age: 25  
  Interests: ['Sports', 'Music', 'Hiking', 'Travel', 'Cooking', 'Movies', 'Reading']
  
- **Female Profile (User 175)**:  
  Age: 25  
  Interests: ['Sports', 'Music', 'Travel', 'Hiking', 'Movies', 'Reading', 'Cooking']
  
- **Match Score**: 18.34

---

### Recommendation 8:
- **Male Profile (User 489)**:  
  Age: 33  
  Interests: ['Travel', 'Hiking', 'Reading', 'Sports', 'Music', 'Movies', 'Cooking']
  
- **Female Profile (User 99)**:  
  Age: 33  
  Interests: ['Reading', 'Cooking', 'Sports', 'Hiking', 'Movies', 'Music', 'Travel']
  
- **Match Score**: 18.3

---

### Recommendation 9:
- **Male Profile (User 280)**:  
  Age: 29  
  Interests: ['Travel', 'Hiking', 'Music', 'Sports', 'Reading', 'Cooking', 'Movies']
  
- **Female Profile (User 300)**:  
  Age: 29  
  Interests: ['Cooking', 'Reading', 'Music', 'Hiking', 'Travel', 'Sports', 'Movies']
  
- **Match Score**: 18.29

---

### Recommendation 10:
- **Male Profile (User 92)**:  
  Age: 22  
  Interests: ['Music', 'Hiking', 'Cooking', 'Travel', 'Movies', 'Reading', 'Sports']
  
- **Female Profile (User 205)**:  
  Age: 22  
  Interests: ['Hiking', 'Movies', 'Reading', 'Travel', 'Sports', 'Cooking', 'Music']
  
- **Match Score**: 18.2

---

# 📌 Conclusion

In this article, we’ve taken a journey into the world of dating recommendations and how Python can be a game-changer in making personalized matches. By using data-driven techniques, we’re able to match people based on various factors such as preferences, behaviors, and compatibility traits. The idea is to help users find partners who are more likely to be a great fit, and the tools Python offers make it possible to do this in a smart, efficient way.

Python gives us the power to analyze complex data with its many libraries, allowing us to fine-tune the matchmaking process. By considering personality traits, shared interests, location, and more, we can craft recommendations that feel more meaningful. And the best part? We’re just scratching the surface! With the endless possibilities of machine learning and AI, we can keep improving these systems to make connections even better.

As the online dating world continues to grow, using data to improve matchmaking is only going to become more important. With the help of Python, we're now able to build systems that provide people with the best possible chances of finding that perfect match.

## 🛠️ Technologies Used

- **Python**
- **Pandas, NumPy** – Data manipulation
- **plotly,Matplotlib,** – Data visualization
- **Datetime** – Recency calculation

---
