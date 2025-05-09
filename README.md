# 🏦 Banking Customer Data Analysis using Python

This project performs **Exploratory Data Analysis (EDA)** on a banking customer dataset using Python libraries such as `pandas`, `matplotlib`, `seaborn`, and `numpy`. The aim is to gain insights into customer behavior, income segmentation, account types, and other key banking attributes.
---

## 🔍 Objective

- Understand the structure and quality of banking customer data
- Segment customers based on income using binning techniques
- Visualize distributions of categorical and numerical variables
- Identify correlations between account features
- Provide insights for decision-making in banking operations

---

## 🛠️ Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Key Tasks Performed

### ✅ Data Preprocessing
- Loaded CSV dataset using `pandas`
- Explored data using `.info()`, `.describe()`, `.head()`

### ✅ Feature Engineering
- Created `Income Band` column by binning `Estimated Income` into: Low, Medium, High

### ✅ Categorical Analysis
- Value counts for features like:
  - Gender
  - Nationality
  - Fee Structure
  - Occupation
- Countplots and histograms for visual distribution

### ✅ Numerical Analysis
- Histograms with KDE for columns like:
  - Estimated Income
  - Credit Card Balance
  - Bank Loans
  - Business Lending

### ✅ Correlation Analysis
- Heatmap showing correlations between numerical features like:
  - Estimated Income vs. Bank Deposits
  - Bank Loans vs. Credit Card Balance


