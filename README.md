# -AIML-Internship-Week3--SamiUrRehmanKhan
Feature Engineering and EDA project on the Ames Housing Dataset using Python. Includes data cleaning, feature engineering, encoding, scaling, skewness reduction, feature selection, and professional visualizations to create an optimized ML-ready dataset for house price prediction.

# 🏠 House Price Prediction — Feature Engineering & EDA Project

## 📌 Dataset Name
**Ames Housing Dataset**  
This dataset contains detailed residential housing data used to analyze factors affecting house prices and to prepare a machine learning-ready dataset through feature engineering and preprocessing.

---

# 📊 Project Overview

This project performs a complete data preprocessing and feature engineering pipeline on the Ames Housing dataset, including:

- Exploratory Data Analysis (EDA)
- Missing value treatment
- Feature engineering
- Encoding categorical variables
- Skewness analysis & transformations
- Feature scaling
- Correlation analysis
- Multicollinearity removal
- Feature selection
- Professional dashboard visualizations

The final output is a clean, optimized dataset prepared for machine learning models.

---

# 🔍 5 Key Findings

## 1. Overall Quality Strongly Influences SalePrice
`OverallQual` showed the strongest correlation with house prices (~0.81), indicating that construction/material quality is the most important pricing factor.

---

## 2. Larger Houses Tend to Sell for Higher Prices
Features like:
- `TotalSF`
- `GrLivArea`
- `GarageArea`

showed strong positive relationships with `SalePrice`.

---

## 3. SalePrice Was Highly Right-Skewed
The original target variable had:
- **Skewness = 1.88**

After applying transformations:
- **Box-Cox reduced skewness to nearly 0**

This improved statistical stability and ML readiness.

---

## 4. Many Features Were Highly Skewed
More than **70% of numerical features** had high skewness, requiring logarithmic transformations to normalize distributions.

---

## 5. Feature Engineering Significantly Improved Predictive Power
Engineered features like:
- `TotalSF`
- `TotalBaths`
- `PricePerSF`

showed strong correlations with the target variable and improved dataset quality.

---

# 🛠️ Top 3 Features Engineered

| Feature | Formula | Purpose |
|---|---|---|
| **TotalSF** | Basement + 1st Floor + 2nd Floor | Captures total house area |
| **TotalBaths** | Weighted bathroom count | Represents complete bathroom utility |
| **PricePerSF** | SalePrice / TotalSF | Measures property efficiency/value |

---

# ⚙️ Tools & Libraries Used

## Programming Language
- Python

## Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

## Development Environment
- Jupyter Notebook

## Documentation
- LaTeX (Overleaf compatible)

---

# 📈 Dashboard Screenshot

![Professional Dashboard](figures/final_dashboard.png)

---

# 📂 Project Workflow

1. Data Cleaning
2. Missing Value Handling
3. Feature Engineering
4. Encoding Techniques
5. Scaling Comparisons
6. Skewness Reduction
7. Correlation Analysis
8. Feature Selection
9. Final Visualization Dashboard

---

# ✅ Final Outcome

- 152 processed numerical features
- Reduced multicollinearity
- Reduced skewness
- ML-ready dataset
- Professional analytical dashboard
- Fully documented feature engineering pipeline

---

# 👨‍💻 Author

**Sami ur Rehman Khan**  
Master's in Data Science — FAST University
