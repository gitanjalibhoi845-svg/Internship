# Customer Churn Prediction System

## Project Overview

The **Customer Churn Prediction System** is a Machine Learning project developed to predict whether a customer is likely to leave a company's services based on customer demographics, subscription details, service usage, and satisfaction level.

The project demonstrates the complete Machine Learning workflow, including synthetic dataset generation, data preprocessing, exploratory data analysis (EDA), visualization, model training, evaluation, and an interactive prediction system.

---

# Problem Statement

Customer churn is one of the biggest challenges faced by subscription-based businesses. Losing existing customers affects revenue and business growth.

The objective of this project is to identify customers who are likely to churn so that companies can take preventive actions to improve customer retention.

---

# Objectives

* Generate a synthetic dataset with 3000+ customer records.
* Clean and preprocess the dataset.
* Perform Exploratory Data Analysis (EDA).
* Visualize customer behavior patterns.
* Train a Machine Learning classification model.
* Predict customer churn using customer information.
* Evaluate model performance using standard metrics.
* Develop a console-based prediction system.

---

# Dataset Information

The dataset was synthetically generated using **NumPy** and **Pandas**.

### Features

* CustomerID
* Age
* Gender
* SubscriptionType
* MonthlyCharges
* TenureMonths
* SupportTickets
* PaymentMethod
* SatisfactionScore
* UsageHoursPerWeek
* Churn (Target Variable)

---

# Dataset Generation Process

A synthetic dataset was created with realistic customer behavior patterns.

Customers with:

* Low satisfaction score
* Low service usage
* Short tenure
* High number of support tickets
* Basic subscription

were assigned a higher probability of churn.

The dataset was saved as:

```text
customer_churn_dataset.csv
```

---

# Technologies & Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

# Project Structure

```text
Customer-Churn-Prediction/
│
├── customer_churn_dataset.csv
├── Customer_Churn_Prediction.ipynb
├── churn_prediction.py
├── README.md
└── images/
```

---

# Data Preprocessing

The following preprocessing steps were performed:

* Handling missing values
* Removing duplicate records
* Label Encoding for categorical variables
* Data validation
* Feature preparation for machine learning

---

# Exploratory Data Analysis (EDA)

The following analyses were performed:

* Churn Distribution
* Tenure vs Churn Analysis
* Subscription-wise Churn Analysis
* Satisfaction Score Impact
* Feature Correlation Analysis

---

# Data Visualizations

The project includes the following visualizations:

* Churn Distribution Pie Chart
* Churn by Subscription Type (Bar Chart)
* Correlation Heatmap
* Monthly Charges Histogram

Optional Visualizations:

* Customer Usage Analysis
* Satisfaction Score Distribution
* Tenure vs Churn Scatter Plot

---

# Machine Learning Model

The project uses the **Random Forest Classifier**.

### Workflow

1. Data Splitting (80% Training / 20% Testing)
2. Model Training
3. Prediction
4. Performance Evaluation

---

# Model Evaluation Metrics

The model was evaluated using:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

# Interactive Prediction System

The console application accepts the following user inputs:

* Age
* Subscription Type
* Monthly Charges
* Tenure Months
* Support Tickets
* Satisfaction Score
* Usage Hours Per Week

The system predicts:

* **Customer Likely to Stay**
* **Customer Likely to Churn**

Input validation and exception handling are included to prevent invalid entries and runtime errors.

---

# Installation Instructions

Clone the repository:

```bash
git clone https://github.com/your-username/Customer-Churn-Prediction.git
```

Navigate to the project folder:

```bash
cd Customer-Churn-Prediction
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

# How to Run the Project

1. Open the Jupyter Notebook (`Customer_Churn_Prediction.ipynb`) or the Python script (`churn_prediction.py`).
2. Run all cells or execute the script.
3. The dataset will be generated.
4. Visualizations will be displayed.
5. The model will be trained and evaluated.
6. Enter customer details in the console to obtain a churn prediction.

---

# Results

The Random Forest Classifier successfully learned customer behavior patterns and predicted whether a customer is likely to churn or remain with the company.

The project achieved reliable classification performance using multiple evaluation metrics.

---

# Key Insights

* Lower customer satisfaction increases churn probability.
* Customers with shorter tenure are more likely to churn.
* Frequent support tickets are associated with higher churn.
* Premium and Enterprise subscribers generally have lower churn rates.
* Higher weekly usage improves customer retention.

---

# Future Improvements

* Use real-world telecom or banking datasets.
* Apply advanced algorithms such as XGBoost or LightGBM.
* Perform hyperparameter tuning.
* Deploy the model using Flask or Streamlit.
* Create an interactive dashboard using Power BI or Tableau.
* Integrate the model with live customer databases.

---

# Author

**Gitanjali Bhoi**

Machine Learning Internship Project

---

# License

This project is developed for educational and internship purposes.
