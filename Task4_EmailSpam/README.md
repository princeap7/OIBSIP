# Email Spam Detection using Machine Learning

---

## Problem Statement

Spam emails, also known as junk emails, are unsolicited messages sent in bulk, often containing advertisements, scams, or phishing attempts.

The objective of this project is to build a **machine learning model** that can accurately classify emails as **spam or not spam (ham)** based on their textual content.

---

## Approach

* Loaded and explored the dataset
* Cleaned and preprocessed the text data
* Converted text into numerical features using **TF-IDF**
* Encoded labels (spam/ham) into numerical values
* Performed exploratory data analysis (EDA)
* Analyzed patterns in spam vs non-spam messages
* Trained a classification model (**Naive Bayes**)
* Evaluated model performance using classification metrics

---

## Data Preprocessing

* Removed unnecessary columns
* Renamed columns (`v1 → label`, `v2 → message`)
* Converted labels:

  * `ham → 0`
  * `spam → 1`
* Cleaned text data:

  * Lowercasing
  * Removing punctuation and special characters
* Converted text into numerical form using **TF-IDF Vectorization**

---

## Exploratory Data Analysis (EDA)

* Analyzed distribution of spam vs ham emails
* Observed that majority emails are **non-spam (ham)**
* Studied message length patterns:

  * Spam messages are often longer and contain promotional words
* Identified common spam keywords:

  * “FREE”, “WIN”, “OFFER”, “URGENT”

---

## Model Building

* Split dataset into training and testing sets (80:20)
* Applied **Multinomial Naive Bayes** model
* Trained model on TF-IDF features
* Generated predictions on test data

---

## Model Evaluation

* Evaluated performance using:

  * **Accuracy**
  * **Precision**
  * **Recall**
  * **F1-score**

* Visualized:

  * Confusion Matrix for classification results

---

## Key Insights

* Text data must be converted into numerical form using **TF-IDF**
* Spam messages often contain promotional and urgent language
* Naive Bayes performs efficiently for text classification problems
* High accuracy (~95–98%) can be achieved with proper preprocessing

---

## Technologies Used

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn

---

## Conclusion

This project demonstrates how machine learning and natural language processing (NLP) can be used to detect spam emails effectively.

The model helps in filtering unwanted messages and provides a foundation for building intelligent email filtering systems.
