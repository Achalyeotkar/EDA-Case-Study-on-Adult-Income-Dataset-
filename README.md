# 📊 Exploratory Data Analysis on the Adult Income Dataset

Welcome! This repository contains a detailed Exploratory Data Analysis (EDA) project on the **Adult Income Dataset** using Python. This case study is a part of my journey as an aspiring Data Analyst, focusing on data cleaning, exploration, visualization, and basic encoding techniques.

---

## 📁 Dataset Information

The **Adult Income Dataset** (also known as the Census Income dataset) is extracted from the 1994 U.S. Census database. The objective is to predict whether an individual's income exceeds \$50K per year based on various attributes.

- **Rows:** 48,842
- **Columns:** 15
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/adult)

---

## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

---

## 🔍 EDA Tasks Covered

1. **Basic Data Exploration**
   - `data.head()`, `data.tail()`, `data.info()`, `data.shape`
2. **Random Sampling**
   - `data.sample(frac=0.5, random_state=111)`
3. **Missing Value Handling**
   - Replaced `'?'` with `NaN`, visualized nulls using `sns.heatmap()`
4. **Data Cleaning**
   - Dropped rows with missing values
   - Removed duplicate records
5. **Descriptive Statistics**
   - Used `data.describe()` and value counts
6. **Column-wise Exploration**
   - Age distribution, education levels, workclass breakdown
7. **Encoding**
   - Converted `income` column into binary format (0 and 1)
8. **Data Type Optimization**
   - Converted object columns like `workclass` to category
9. **Univariate and Bivariate Analysis**
   - Histograms, boxplots, countplots

---

## 📈 Sample Visualizations

- Age distribution histogram
- Income vs Age boxplot
- Workclass distribution plot
- Null value heatmap

---

## 📌 Key Insights

- Majority of the individuals are aged between 25–45.
- Most of the individuals work in the **Private sector**.
- Around **75%** of individuals earn less than \$50K/year.
- Significant missing data in `workclass`, `occupation`, and `native-country`.

---



