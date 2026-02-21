# 💻 Laptop Price Prediction with Ridge Regression

This project aims to predict laptop prices based on technical specifications such as RAM, SSD, Processor, and Brand. Using various Machine Learning techniques, I achieved a robust prediction model with an **R² score of 77.5%**.

## 🚀 Project Overview
As a Computer Programming student at Ankara Medipol University, this project represents my first end-to-end Machine Learning factory. It covers the entire pipeline from data cleaning to advanced regularization techniques.

## 🛠️ Tech Stack
* **Python** (Core Logic)
* **Pandas & NumPy** (Data Manipulation)
* **Scikit-Learn** (Machine Learning Models)
* **Matplotlib & Seaborn** (Data Visualization)

## 📊 Methodology & Progress
The project followed an iterative approach to find the best model:

1. **Data Cleaning:** Developed a custom `df_cleaner` function to handle hardware specifications and categorical encoding.
2. **Exploratory Data Analysis (EDA):** Identified strong positive correlations between Price, RAM, and SSD.
3. **Linear Regression:** Baseline model achieved a **67%** accuracy.
4. **Polynomial Features (Degree 2):** Attempted to capture non-linear relationships, but faced overfitting issues with a drop to **47%**.
5. **Regularization (Ridge & Lasso):** Implemented `StandardScaler` and `RidgeCV` to handle high-dimensional polynomial data.

## 🏆 Final Results
The **RidgeCV** model outperformed others by effectively managing multicollinearity and complexity:
* **Initial R² Score:** 0.67
* **Final Optimized R² Score:** **0.775**

> "Like a boxing match, the model learned to stay balanced even when the data got complex!" - A note from my development logs.

## 📫 Contact
**Burak Alaca** - Computer Programming Student
