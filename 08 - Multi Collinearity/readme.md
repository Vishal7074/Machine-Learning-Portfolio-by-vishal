# Multicollinearity in Machine Learning using California Housing Dataset

## 📖 Project Overview

This project provides a practical and in-depth understanding of **Multicollinearity** in Machine Learning using the **California Housing Dataset**.

Instead of only explaining the theory, this notebook demonstrates how multicollinearity affects Linear Regression models, how to detect it using statistical techniques, and how to solve it using multiple approaches.

The notebook follows a complete data analysis workflow, making it suitable for beginners as well as anyone preparing for Machine Learning interviews.

---

## 📂 Dataset

**Dataset:** California Housing Dataset

The dataset contains housing-related information such as:

* Longitude
* Latitude
* Housing Median Age
* Total Rooms
* Total Bedrooms
* Population
* Households
* Median Income
* Ocean Proximity
* Median House Value (Target)

---

## 🚀 Topics Covered

### 1. Data Loading & Exploration

* Load the California Housing dataset
* Understand the features
* Basic preprocessing

### 2. Linear Regression Baseline Model

* Train a Linear Regression model
* Calculate R² Score
* Analyze feature coefficients

### 3. Understanding Multicollinearity

* What is Multicollinearity?
* Why it is harmful for Linear Regression
* Effect on model coefficients

### 4. Correlation Analysis

* Correlation Matrix
* Identifying highly correlated features

### 5. Variance Inflation Factor (VIF)

* Calculate VIF for every feature
* Interpret VIF values
* Identify multicollinear variables

### 6. Removing Multicollinearity

* Remove high VIF features
* Recalculate VIF
* Repeat until acceptable VIF values are achieved

### 7. Model Comparison

* Train the model before removing multicollinearity
* Train the model after removing multicollinearity
* Compare performance and coefficients

### 8. Principal Component Analysis (PCA)

* Apply PCA as an alternative solution
* Understand dimensionality reduction
* Compare results

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Statsmodels
* Jupyter Notebook

---

## 📌 Project Workflow

```text
California Housing Dataset
            │
            ▼
     Data Cleaning
            │
            ▼
 Exploratory Data Analysis
            │
            ▼
  Linear Regression Model
            │
            ▼
 Correlation Analysis
            │
            ▼
      Calculate VIF
            │
            ▼
 Remove High VIF Features
            │
            ▼
 Retrain Linear Regression
            │
            ▼
 Compare Model Performance
            │
            ▼
      Apply PCA
            │
            ▼
   Final Evaluation
```

---

## 🎯 Learning Outcomes

After completing this notebook, you will understand:

* What multicollinearity is and why it occurs.
* How correlated features affect Linear Regression.
* How to interpret VIF values.
* How to remove multicollinearity step by step.
* How feature coefficients change after removing multicollinearity.
* When PCA should be used as an alternative.
* How professional data scientists handle multicollinearity in real-world projects.

---

## 📈 Key Concepts

* Linear Regression
* Multicollinearity
* Correlation Matrix
* Variance Inflation Factor (VIF)
* Feature Selection
* PCA (Principal Component Analysis)
* Model Evaluation
* Coefficient Interpretation

---

## 📌 Future Improvements

This project can be extended by implementing:

* Ridge Regression
* Lasso Regression
* Elastic Net
* Pipeline
* Cross Validation
* GridSearchCV
* Feature Engineering

---

## 👨‍💻 Author

**Vishal Vishwakarma**

This project is a part of my Machine Learning Portfolio, where I implement Machine Learning concepts from scratch with detailed explanations and practical examples.

If you found this project helpful, consider giving it a ⭐ on GitHub.
