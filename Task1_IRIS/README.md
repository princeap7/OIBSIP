# 🌸 Iris Flower Classification using Machine Learning

---

## Problem Statement

The Iris dataset contains measurements of iris flowers, including sepal length, sepal width, petal length, and petal width.

The objective of this project is to build a **Machine Learning classification model** that can accurately predict the species of an iris flower:

* Setosa
* Versicolor
* Virginica

---

## Approach

* Loaded the dataset using Scikit-learn
* Performed exploratory data analysis (EDA)
* Visualized feature relationships using plots
* Split data into training and testing sets
* Trained a classification model
* Evaluated model performance using standard metrics

---

## Data Preprocessing

* Checked for missing values (dataset was clean)
* Converted target labels into meaningful class names
* Separated features and target variables
* Applied train-test split for model evaluation

---

## Model Used

* **Logistic Regression**

Reason:

* Simple and effective for classification problems
* Works well with linearly separable data like Iris dataset

---

## Evaluation

* Accuracy Score
* Confusion Matrix
* Classification Report

### Results

* **Accuracy:** ~97% – 100%
* Perfect classification observed in most cases

---

## Model Testing (Custom Input)

The model was tested with sample inputs:

* Sample 1 → Setosa
* Sample 2 → Versicolor
* Sample 3 → Virginica

The model correctly predicted all classes, demonstrating strong generalization.

---

## Key Insights

* Petal length and petal width are the most important features
* Setosa is easily separable from other species
* Versicolor and Virginica have slight overlap but are still distinguishable

---

## Technologies Used

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn

---

## Conclusion

This project demonstrates how machine learning can be used to solve classification problems effectively.
The model achieved high accuracy and successfully classified iris species based on input features.

---