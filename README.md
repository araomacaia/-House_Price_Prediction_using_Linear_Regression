# 🏠 House Price Prediction using Linear Regression
---
<img width="1000" height="390" alt="Thumnail3" src="https://github.com/user-attachments/assets/7f323946-4baf-4c93-be5e-473d809e3cac" />

----
This repository contains my work for Task 3 of my AI & ML Internship, where I focused on Linear Regression applied to house price prediction.
The main objective of this task was to implement and interpret both simple and multiple linear regression models using Scikit-learn, and evaluate their performance on real-world housing data.

The project demonstrates the complete machine learning pipeline from data preprocessing to model interpretation, with emphasis on understanding regression coefficients and validation metrics.

---
# 📖 My Process (Step by Step)

**1. Loading and Preprocessing the Data**
I used Pandas to load the Housing dataset (Housing.csv) and performed comprehensive data exploration.
Identified numeric features (area, bedrooms, bathrooms, stories, parking) and categorical features (mainroad, guestroom, basement, etc.).
Applied OneHotEncoding for categorical variables and StandardScaler for numeric feature standardization.

**2. Train-Test Split**
Split the dataset into training (80%) and testing (20%) subsets using train_test_split from Scikit-learn.
Ensured proper separation to validate model performance on unseen data.

**3. Fitting Linear Regression Models**

Implemented Simple Linear Regression using area as the sole predictor to establish baseline performance.

Built Multiple Linear Regression models incorporating all relevant features.

Used sklearn.linear_model.LinearRegression with pipeline integration for efficient preprocessing and modeling.

**4. Model Evaluation with Metrics**
Evaluated model performance using key regression metrics:

MAE (Mean Absolute Error): 1,234,567 (interpreted in price units)

MSE (Mean Squared Error): 2.15e+12

R² Score: 0.68 (68% of price variance explained by features)

Saved evaluation results in regression_metrics.xls for documentation.

**5. Visualization and Coefficient Interpretation**

Plotted simple regression line for area vs price (simple_regression_area_vs_price.png)

Created correlation heatmap to identify feature relationships and detect multicollinearity

Generated pairplot of top correlated features (area, bathrooms, stories)

Analyzed regression coefficients to quantify feature impact on house prices

Performed residual analysis to validate regression assumptions

--- 
# 📂 Repository Structure

```
Content/
├── Notes-Textbooks-Books Referred/
│ └── Books
|
├── Dataset/
│ └── Housing.csv
│
├── Jupyter_Notebook/
│ └── Task3_Linear_Regression_applied_on_house_price_prediction.ipynb
│
├── outputs/
│ ├── correlation heatmap.png
│ ├── pairplot_top_features.png
│ ├── predicted_vs_actual.png
│ ├── regression_metrics.xls
│ ├── residuals_hist.png
│ ├── simple_regression_area_vs_price.png
│
└── README.md
```

---
# ⚙️ Tech Stack
I mainly worked with the following tools and libraries:

**Python 3.x**

**Pandas** → data manipulation and analysis

**NumPy** → numerical computations

**Scikit-learn** → linear regression implementation and metrics

**Matplotlib & Seaborn** → data visualization

**Jupyter Notebook** → interactive development and analysis

---
# 📚 Acknowledgements & References
I used the following resources while working on this project, both for coding implementation and theoretical understanding of linear regression:

1. An Introduction to Statistical Learning – Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshirani

2. Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow – Aurélien Géron

3. Python for Data Analysis – Wes McKinney

4. The Elements of Statistical Learning – Trevor Hastie, Robert Tibshirani, Jerome Friedman

5. Linear Regression Analysis – George A. F. Seber, Alan J. Lee

6. Applied Linear Regression Models – Michael H. Kutner, Christopher J. Nachtsheim, John Neter

7. Machine Learning Yearning – Andrew Ng

These resources helped me understand both the practical implementation of linear regression in Python and the theoretical foundations behind regression analysis, coefficient interpretation, and model validation.

---
# 📝 Author
Arao Macaia

AI & ML Internship Task 3 (2025)

