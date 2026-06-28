# Big Mart Sales Prediction Using Machine Learning

**Internship Project — Artificial Intelligence Domain**  
Submitted by **Harshit** | Vijay Patil School of Management, Navi Mumbai  
Organization: Naviotech Solution Pvt. Ltd. | June 2026

## 📌 Project Overview

To predict the sales of products across different Big Mart outlets based on product and store attributes, helping the business understand the factors that drive sales.

## 🎯 Objectives

- Analyze and understand the dataset
- Clean and preprocess the data
- Build a model using **XGBoost Regressor (Extreme Gradient Boosting)**
- Train the model and make predictions
- Evaluate the model's performance

## 📊 Dataset Information

The Big Mart Sales dataset containing 8,523 records of products sold across 10 stores. Each record describes a product and the outlet it was sold in, along with its sales figure.

**Key features:**

- Item Identifier & Weight
- Item Fat Content
- Item Visibility
- Item Type & MRP
- Outlet Identifier
- Outlet Establishment Year
- Outlet Size & Location Type
- Outlet Type

**Target: Item_Outlet_Sales (the sales amount to be predicted)**

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Google Colab / Jupyter Notebook

## 🔄 Project Workflow

1. Data Collection
2. Data Preprocessing & Cleaning
3. Feature Preparation
4. Train-Test Split
5. Model Building
6. Model Training
7. Prediction
8. Performance Evaluation

## 🤖 Model

**Algorithm used:** XGBoost Regressor (Extreme Gradient Boosting)

## 📈 Results

| Metric | Value |
|--------|-------|
| R² Score (Test) | **0.59** |
| R² Score (Training) | **0.64** |

After data cleaning, label encoding and feature engineering, an XGBoost Regressor was trained. It achieved an R-squared score of about 0.64 on training data and 0.59 on test data, indicating the model explains a reasonable portion of the variation in product sales.

## ▶️ How to Run

1. Open the `.ipynb` notebook in Google Colab or Jupyter Notebook.
2. Upload the dataset file(s) included in this repository.
3. Run all cells from top to bottom.
4. View the predictions and accuracy results.

## 🚀 Future Scope

- Use larger and more diverse datasets
- Try advanced models and hyperparameter tuning
- Deploy the model as a web application for real-time use

## 👨‍💻 Author

**Harshit**  
Master of Business Administration (MBA), Vijay Patil School of Management, Navi Mumbai  
Internship Project Submission — Naviotech Solution Pvt. Ltd., June 2026