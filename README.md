# Exploratory Data Analysis (EDA) on Sales Dataset

## 🔍 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a structured sales dataset to understand data distribution, detect outliers, identify relationships between variables, and extract meaningful business insights.

The analysis demonstrates how raw business data can be transformed into insights using **Python-based data analysis and visualization techniques**.

---

## 🎯 Objective
- Understand the structure and characteristics of the dataset
- Perform descriptive statistical analysis
- Identify outliers and unusual patterns
- Analyze distributions of numerical and categorical variables
- Explore relationships between sales, profit, discounts, and quantity
- Generate actionable insights for business decision-making

---

## 📊 Dataset Overview
- **Type:** Tabular sales dataset
- **Key Numerical Features:**
  - Sales
  - Profit
  - Quantity
  - Discount
- **Key Categorical Features:**
  - Region
  - Category
  - Sub-Category

> The dataset represents transactional sales data commonly used in retail/business analytics.

---

## 🔄 Analysis Workflow

### 1. Data Loading & Inspection
- Imported dataset using pandas
- Displayed first few rows
- Checked number of rows and columns
- Verified data types and structure

---

### 2. Descriptive Statistics
- Computed:
  - Mean
  - Standard deviation
  - Variance
- Focused analysis on the **Sales** column
- Identified data spread and central tendency

---

### 3. Outlier Detection
- Used **boxplots** to detect outliers in:
  - Sales
  - Profit
- Observed presence of extreme values, common in sales datasets

---

### 4. Categorical Data Analysis
- Generated **frequency tables** for:
  - Region
  - Category
  - Sub-Category
- Identified most frequent product categories and regions

---

### 5. Univariate Analysis
- Plotted **histograms** for:
  - Sales
  - Quantity
  - Discount
  - Profit
- Analyzed skewness and distribution patterns

---

### 6. Bivariate Analysis
- Computed **correlation matrix**
- Visualized correlations using a heatmap
- Studied relationships between:
  - Sales & Profit
  - Discount & Profit
  - Quantity & Sales

---

## 📈 Key Insights
- Sales and Profit show a positive correlation
- High discounts often impact profit negatively
- Sales distribution is right-skewed, indicating few high-value transactions
- Certain categories and regions dominate overall sales volume
- Outliers are present and should be handled carefully in modeling tasks

---

## 🛠️ Tools & Technologies
- **Python**
- **Pandas** – data manipulation
- **NumPy** – numerical computations
- **Matplotlib** – basic visualizations
- **Seaborn** – advanced statistical plots

---

## 📁 Project Structure
​
