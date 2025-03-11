# Logistic-Regression-Model
This repository contains a Python script that implements Logistic Regression to predict whether a customer will make a purchase based on demographic and behavioral factors.


# Logistic Regression Model

## Overview
This repository contains a Python script that implements **Logistic Regression** to predict whether a customer will make a purchase based on demographic and behavioral factors.

---

## **Problem Statement**
Businesses need to identify potential buyers based on customer characteristics. This project aims to build a **Logistic Regression** model to predict purchase behavior based on factors like age, income, website engagement, and discounts availed.

### **Dataset Description**
The dataset used in this project is from [**Kaggle: Predict Customer Purchase Behavior Dataset**](https://www.kaggle.com/datasets/rabieelkharoua/predict-customer-purchase-behavior-dataset) and includes the following features:
- **Age**: Customer's age.
- **Gender**: 0 = Male, 1 = Female.
- **Annual Income ($)**: Customer's annual income in dollars.
- **Time Spent on Website**: Time spent on the website (in minutes).
- **Loyalty Program**: 0 = No, 1 = Yes.
- **Discounts Availed**: Number of discounts used (0–5).
- **PurchaseStatus (Target Variable)**:
  - **1**: Customer made a purchase.
  - **0**: Customer did not make a purchase.

---

## **How the Script Works**
1. **Data Preparation**:
   - Loads the dataset and checks for missing values.
   - Fills missing values using mean imputation.
2. **Model Training**:
   - Splits the dataset into **training (80%)** and **testing (20%)** sets.
   - Trains a **Logistic Regression** model using `sklearn.linear_model.LogisticRegression()`.
3. **Prediction & Evaluation**:
   - Makes predictions on the test dataset.
   - Evaluates the model using:
     - **Confusion Matrix**
     - **Precision, Recall, and F1-score**
     - **Classification Report**
4. **Feature Importance Analysis**:
   - Analyzes the impact of each feature on the prediction.
5. **Visualization**:
   - **Confusion Matrix Heatmap**
   - **Feature Importance Bar Chart**

---

## **Dependencies**
Ensure you have the following Python libraries installed:
```sh
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## **How to Run the Script**
1. Clone the repository:
   ```sh
   git clone <repository_url>
   ```
2. Navigate to the project folder:
   ```sh
   cd <project_folder>
   ```
3. Run the Python script:
   ```sh
   python logistic_regression.py
   ```
4. Follow the output to view predictions and model evaluation.

---

## **Contributing**
Contributions are welcome! Feel free to fork this repository and submit a pull request with improvements or additional features.


