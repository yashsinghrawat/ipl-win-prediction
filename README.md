# IPL Win Prediction

A Machine Learning project that predicts the **winning probability of IPL teams at any given point during a match** based on match and team statistics.

---

## 📌 Project Overview
This project uses historical IPL match data to estimate the probability of a team winning a match in real time.  
It applies supervised machine learning techniques to analyze match conditions such as runs, wickets, overs, and team performance.

The model is designed to assist in **sports analytics and decision-making** by providing data-driven insights.

---

## ❓ Problem Statement
Given the current match situation (score, wickets, overs remaining, teams playing), predict the **probability of winning** for both teams.

---

## 📊 Dataset
- Source: Kaggle IPL Dataset (2008–2024)
- Data includes:
  - Match details
  - Team information
  - Runs, wickets, overs
  - Match outcomes

---

## 🧠 Machine Learning Approach
- Data cleaning and preprocessing
- Feature engineering
- Model training and evaluation
- Probability prediction instead of just binary outcome

### Models Used
- Logistic Regression
- Random Forest Classifier
- XGBoost (if applicable)

---

## 🧩 Features Used
- Batting team
- Bowling team
- Runs scored
- Wickets lost
- Overs completed
- Target score
- Runs remaining
- Balls remaining
- Required run rate
- Current run rate

---

## ⚙️ Tech Stack
- **Programming Language:** Python
- **Libraries:**  
  - Pandas  
  - NumPy  
  - Scikit-learn  
  - Matplotlib  
  - Seaborn  
- **Tools:** Jupyter Notebook / VS Code

---

## 🚀 How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/IPL-Win-Prediction.git
cd IPL-Win-Prediction
