# Car Price Prediction using Machine Learning

---

## Problem Statement

The price of a car depends on multiple factors such as the goodwill of the brand, features of the car, engine specifications, horsepower, and mileage.

The objective of this project is to build a **machine learning model** that can accurately predict the price of a car based on these features using regression techniques.

---

## Approach

- Loaded and explored the dataset  
- Cleaned and preprocessed the data  
- Extracted useful features (e.g., brand from car name)  
- Converted categorical variables into numerical form  
- Performed exploratory data analysis (EDA)  
- Visualized relationships between features and price  
- Trained a regression model (Linear Regression)  
- Evaluated model performance using standard metrics  

---

## Data Preprocessing

- Removed unnecessary columns (`car_ID`, `CarName`)  
- Extracted **brand name** as a new feature  
- Converted categorical variables using **Label Encoding**  
- Checked and handled missing values  
- Scaled features using **StandardScaler**  

---

## Exploratory Data Analysis (EDA)

- Analyzed distribution of car prices  
- Identified key features influencing price:
  - Engine size  
  - Horsepower  
  - Curb weight  
- Observed negative correlation with:
  - Mileage (`citympg`, `highwaympg`)  
- Used correlation heatmap for feature relationships  

---

## Model Building

- Split dataset into training and testing sets (80:20)  
- Applied **Linear Regression** model  
- Trained model on scaled data  
- Generated predictions on test data  

---

## Model Evaluation

- Evaluated performance using:
  - **R² Score**
  - **Mean Absolute Error (MAE)**
  - **Mean Squared Error (MSE)**  

- Visualized:
  - Actual vs Predicted prices (scatter plot)

---

## Key Insights

- Features like **engine size, horsepower, and weight** strongly increase price  
- Higher mileage cars tend to have **lower prices**  
- Brand significantly affects pricing  
- Linear Regression provides good baseline accuracy (~80–90%)  

---

## Technologies Used

- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  

---

## Conclusion

This project demonstrates how machine learning can be used to predict car prices based on various influencing factors.  

The model helps understand feature importance and provides a foundation for more advanced predictive systems.

---