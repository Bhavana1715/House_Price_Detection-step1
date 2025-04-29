# 🏡 House Prices EDA – Data Analysis Phase

Welcome to the exploratory data analysis (EDA) phase of the **House Prices - Advanced Regression Techniques** project. This notebook is focused on understanding the structure, patterns, and relationships within the data to lay a solid foundation for the upcoming feature engineering and model building phases.

---

## 📂 Dataset Used

- **File:** `train.csv`
- **Source:** [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
- **Rows:** 1460
- **Columns:** 81  
- **Target Variable:** `SalePrice`

---

## 📊 Objectives of This Analysis

1. Identify and visualize **missing values**.
2. Understand **numerical** and **categorical** features.
3. Explore **distribution patterns** of variables.
4. Detect **outliers** in numerical variables.
5. Investigate **cardinality** of categorical features.
6. Analyze **temporal (year-based)** trends.
7. Study **relationships** between independent features and `SalePrice`.

---

## 🔍 Key Steps Performed

### ✅ Data Loading and Setup
- Loaded the dataset using `pandas`.
- Enabled full column visibility and added scrollable DataFrame display.

### 🔎 Missing Values
- Calculated total and percentage of missing values.
- Visualized their impact on `SalePrice`.
- Found that some missing values strongly correlate with price — will be carefully handled during feature engineering.

### 🔢 Numerical Variables
- Identified all numeric columns.
- Separated `year` features for further analysis.

### ⏳ Temporal Variables
- Investigated the influence of variables like `YearBuilt`, `YearRemodAdd`, etc.
- Observed relationships with `SalePrice` using scatter plots.

### 🧮 Discrete vs Continuous Features
- **Discrete Features:** Few unique values, visualized using bar plots.
- **Continuous Features:** Broad value range, visualized with histograms.

---

## 📌 Libraries Used

```python
pandas        # For data manipulation
numpy         # For numerical operations
matplotlib    # For plotting
seaborn       # For advanced visualizations
```

---

## 📈 Sample Visuals

- **Missing Value Impact**
- **Median SalePrice per Feature**
- **Year Sold vs SalePrice Line Plot**
- **Scatter Plots: Year Features vs SalePrice**
- **Bar Charts: Discrete Features vs SalePrice**
- **Histograms: Continuous Features**

---

## 📌 Observations

- Missing values can significantly influence `SalePrice` and must be treated thoughtfully.
- Some year-related features, when transformed, show strong trends with price.
- Discrete features like `OverallQual`, `OverallCond`, etc., have strong predictive potential.
- Continuous features vary widely in distribution and require normalization/scaling later.

---

## 📦 Next Steps

- Handle missing values smartly (based on their observed impact).
- Perform feature engineering on temporal and categorical variables.
- Prepare data for machine learning models.

---

## 🙌 Author Notes

This project is a part of my data science journey to understand feature behavior and improve prediction accuracy. Feedback and suggestions are always welcome!
