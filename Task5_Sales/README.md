# Sales Prediction using Machine Learning

---

## Problem Statement

Sales prediction involves estimating how much of a product will be sold based on various factors such as advertising expenditure, target audience, and advertising platforms.

The objective of this project is to build a **machine learning model** that can accurately predict sales based on advertising data using regression techniques.

---

## Approach

* Loaded and explored the dataset
* Cleaned and preprocessed the data
* Analyzed relationships between advertising channels and sales
* Performed exploratory data analysis (EDA)
* Visualized trends and correlations
* Trained a regression model (**Linear Regression**)
* Evaluated model performance using standard metrics

---

## Data Preprocessing

* Checked dataset for missing values
* Renamed columns if necessary
* Verified data types
* No categorical encoding required (dataset is numerical)
* Scaled features using **StandardScaler** (optional for Linear Regression)

---

## Exploratory Data Analysis (EDA)

* Analyzed distribution of sales
* Studied impact of advertising channels:

  * TV advertising
  * Radio advertising
  * Newspaper advertising
* Observed:

  * Strong correlation between **TV advertising and sales**
  * Moderate correlation with **Radio**
  * Weak correlation with **Newspaper**
* Used correlation heatmap to visualize relationships

---

## Model Building

* Split dataset into training and testing sets (80:20)
* Applied **Linear Regression** model
* Trained model on dataset
* Generated predictions on test data

---

## Model Evaluation

* Evaluated performance using:

  * **R² Score**
  * **Mean Absolute Error (MAE)**
  * **Mean Squared Error (MSE)**

* Visualized:

  * Actual vs Predicted sales (scatter plot)

---

## Key Insights

* **TV advertising** has the highest impact on sales
* **Radio advertising** contributes moderately
* **Newspaper advertising** has minimal effect
* Linear Regression provides strong baseline performance

---

## Technologies Used

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn

---

## Conclusion

This project demonstrates how machine learning can be used to predict product sales based on advertising expenditure.

The model helps businesses make data-driven decisions to optimize their marketing strategies and maximize revenue.

---
