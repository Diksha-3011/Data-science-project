**📊 Netflix India Trend Analysis & Prediction**

**📌 Project Overview**

This project analyzes the popularity trend of Netflix in India using time-series data from Google Trends.
The dataset contains weekly search interest values (0–100) from 2015 to 2020, representing how Netflix's popularity has evolved over time.

**🎯 Objectives**
Analyze Netflix popularity trends in India 📈
Perform data cleaning and preprocessing
Visualize weekly and yearly trends
Categorize popularity levels (Low, Medium, High)
Predict future trends using simple forecasting techniques

**📂 Dataset Information**

Source: Kaggle (Google Trends data)
Columns:
Week → Date (weekly data)
Netflix (India) → Popularity score (0–100)


**🛠️ Technologies Used**
Python 🐍
Pandas
Matplotlib
NumPy
Scikit-learn

**📊 Exploratory Data Analysis (EDA)**
✔ Data Cleaning
Removed unnecessary rows (metadata)
Fixed column names
Converted Week to datetime format
✔ Trend Analysis
Visualized Netflix growth over time
Observed steady increase from 2015 to 2020
✔ Categorization
Divided values into:
Low (0–30)
Medium (30–70)
High (70–100)


**🤖 Prediction Model**

A simple Linear Regression model was used to forecast future Netflix popularity.

Steps:
Converted time into numerical format
Trained model on historical data
Predicted future weekly values
Output:
Predicted values show a gradual upward trend
Values were rounded for better interpretation


**📈 Results & Insights**

Netflix popularity in India increased significantly over time
Major growth observed after 2017
Peak values observed near 2020
Prediction suggests continued gradual growth

**⚠️ Limitations**
Dataset contains only one feature (time)
Predictions are based on trend, not real-world factors
Accuracy is limited due to lack of additional data


**🚀 Future Improvements**
Use advanced models like ARIMA or Prophet
Combine with movie/ratings datasets
Add external factors (events, releases, etc.)




**⭐ Conclusion**

This project demonstrates how time-series data can be used to analyze trends and make basic predictions, even with limited features.
