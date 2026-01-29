# End-to-End Linear Regression with EDA

## 📌 Overview
This repository contains a complete **end-to-end workflow** for predicting continuous target variables using **Linear Regression**. It demonstrates the entire machine learning pipeline, from data exploration to model evaluation, with clear explanations and visualizations.

---

## 🧪 Features
- **Exploratory Data Analysis (EDA):** Visualizing patterns, distributions, and correlations in the dataset.  
- **Data Preprocessing:** Handling missing values, encoding categorical features, and scaling numerical features.  
- **Model Training:** Linear Regression using **Ordinary Least Squares (OLS)**.  
- **Evaluation:** Performance metrics include **R² score**, **Mean Absolute Percentage Error (MAPE)**, and residual plots.  
- **Insights:** Interpreting model coefficients to identify key contributing features.  

---

## 📊 Dataset
The analysis uses a **publicly available real estate / housing price dataset**.  
- The dataset includes features such as location, size, number of bedrooms, bathrooms, and furnishing status.  
  
---

## 🛠 Workflow
1. **Load Dataset:** Import CSV file into pandas DataFrame.  
2. **Exploratory Data Analysis:** Summary statistics, missing values, and visualizations.  
3. **Data Preprocessing:**  
   - Handle missing values  
   - Encode categorical variables using one-hot encoding  
   - Scale numerical features using StandardScaler  
4. **Train-Test Split:** Divide data into training and testing sets.  
5. **Model Training:** Fit Linear Regression model on training data.  
6. **Model Evaluation:**  
   - Calculate R² score and MAPE  
   - Plot best-fit line and predicted vs actual values  
7. **Interpretation & Insights:** Analyze coefficients and identify important features.  

---

## 📈 Results
- **R² Score:** ~0.67  
- **Mean Absolute Percentage Error (MAPE):** ~17.6%  

The results indicate that the model captures the main trend in the data and serves as a strong **baseline for regression tasks**.

---

## 🔮 Future Work
- Apply **Ridge, Lasso, or ElasticNet** regression for regularization  
- Introduce **polynomial features** for non-linear relationships  
- Explore **ensemble methods** such as Random Forest or Gradient Boosting  
- Perform **cross-validation** to improve model robustness  

---

## 🔗 Kaggle Notebook
The full interactive notebook is available on Kaggle:  
[View Notebook on Kaggle](https://www.kaggle.com/code/truptichudasama/end-to-end-linear-regression-with-eda)

---


