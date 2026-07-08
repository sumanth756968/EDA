# Exploratory Data Analysis (EDA) on Cardiotocographic Dataset

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Cardiotocographic (CTG) Dataset** using Python. The analysis focuses on understanding the dataset, cleaning the data, detecting and removing outliers, calculating descriptive statistics, and visualizing relationships between features to gain meaningful insights.

---

## 📂 Project Structure

```
EDA.ipynb                 # Jupyter Notebook containing complete EDA
Cardiotocographic.csv     # Dataset used for analysis
README.md                 # Project documentation
```

---

## 🎯 Objectives

- Load and explore the dataset.
- Understand the dataset structure and summary statistics.
- Detect and handle missing values.
- Remove duplicate records.
- Detect and remove outliers using the IQR method.
- Calculate descriptive statistics.
- Visualize data distributions and feature relationships.
- Analyze feature correlations and target class distribution.

---

## 🛠️ Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📚 Concepts Covered

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Missing Value Analysis
- Duplicate Removal
- Outlier Detection (IQR Method)
- Descriptive Statistics
- Correlation Analysis
- Data Visualization

---

## 📊 Dataset

The project uses the **Cardiotocographic (CTG) Dataset**, which contains fetal heart rate measurements and uterine contraction features used to classify fetal health.

The dataset includes multiple numerical features along with the target variable:

- **NSP** – Fetal Health Class
  - 1 – Normal
  - 2 – Suspect
  - 3 – Pathologic

---

## ⚙️ Workflow

1. Import required libraries.
2. Load the Cardiotocographic dataset.
3. Explore dataset information and summary statistics.
4. Check for missing values and remove duplicate records.
5. Detect and remove outliers using the Interquartile Range (IQR) method.
6. Calculate mean, median, mode, standard deviation, and IQR.
7. Visualize feature distributions using histograms.
8. Generate a correlation heatmap.
9. Analyze class distribution using a pie chart.
10. Create pair plots for important features.
11. Identify features most correlated with the target variable (NSP).

---

## 📈 Visualizations

The notebook includes the following visualizations:

- Histograms for feature distributions
- Correlation Heatmap
- NSP Class Distribution Pie Chart
- Pair Plot of important features
- Correlation analysis with the target variable

---

## 📖 Key Insights

- The dataset was cleaned by removing duplicate records and outliers.
- Descriptive statistics helped summarize the central tendency and variability of each feature.
- Correlation analysis identified features that strongly influence the target class.
- Visualizations provided a clear understanding of feature distributions and relationships.
- The cleaned dataset is suitable for further machine learning model development.

---

a complete exploratory data analysis workflow for the Cardiotocographic dataset. Through data cleaning, statistical analysis, and visualization, it uncovers important patterns, detects anomalies, and highlights relationships among variables. The resulting cleaned dataset provides a strong foundation for predictive modeling and fetal health classification.
