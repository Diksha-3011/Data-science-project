# 🚢 Titanic Survival Prediction (Machine Learning Project)

## 📌 Overview
This project is a classic **binary classification problem** where we predict whether a passenger survived the Titanic disaster or not.

The workflow includes complete **Data Science pipeline**:
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization (Graphs & Insights)
- Machine Learning Model (Logistic Regression)
- Model Evaluation

---

## 🎯 Problem Statement
Given passenger data such as age, gender, ticket class, etc., the goal is to predict:

👉 **Survived (1) or Not Survived (0)**

---

## 📂 Dataset
- Source: :contentReference[oaicite:0]{index=0} Titanic Dataset
- Type: Structured tabular dataset
- Target column: `Survived`

---

## ⚙️ Tech Stack
- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (Logistic Regression)

---

## 🔄 Project Workflow

### 1. Data Cleaning 🧹
- Handled missing values (Age, Embarked)
- Dropped irrelevant columns (Cabin, Ticket, Name)
- Converted categorical variables into numerical form
- Checked data consistency

---

### 2. Exploratory Data Analysis (EDA) 📊
Performed deep analysis to understand survival patterns:

- Survival rate by **Gender**
- Survival rate by **Passenger Class**
- Age distribution of passengers
- Fare distribution
- Correlation between features

---

### 3. Data Visualization 📈
Used graphs to extract insights:
- Count plots for survival comparison
- Heatmap for correlation
- Histogram for age distribution
- Bar charts for class vs survival

📌 Key Insight:
- Females had significantly higher survival rate
- 1st class passengers had better chances of survival
- Fare and class strongly influenced survival

---

### 4. Machine Learning Model 🤖
- Algorithm used: **Logistic Regression**
- Train-Test Split applied
- Model trained on cleaned dataset

---

### 5. Model Evaluation 📉
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

📌 Final Accuracy: **(Add your score here after running model)**

---

## 📊 Sample Insights (EDA Results)
- Women and children had higher survival probability
- 1st class passengers were prioritized during rescue
- Majority of 3rd class passengers did not survive

---

## 🚀 How to Run This Project

```bash
git clone https://github.com/your-username/titanic-survival-prediction.git
