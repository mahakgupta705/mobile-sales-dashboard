# 🍷 Wine Quality Analysis

A Python-based Exploratory Data Analysis (EDA) project on the **Red Wine Quality dataset**, aimed at understanding the physicochemical properties of wine and their relationship with wine quality.

## 🔍 Project Overview

This project performs a complete exploratory analysis of the `winequality-red.csv` dataset, including:

- Loading and inspecting the dataset structure (`info()`, `describe()`, `shape`)
- Checking for missing and duplicate values
- Removing duplicate records for data cleaning
- Analyzing correlations between features using a correlation matrix and heatmap
- Visualizing the distribution of wine quality (class imbalance check)
- Plotting histograms for all numerical features to study their distributions

## 🛠️ Tech Stack

- **Python**
- **Pandas** – data loading & manipulation
- **Matplotlib** – data visualization
- **Seaborn** – statistical visualizations (heatmaps, histograms)

## 📊 Key Steps

1. Data Loading & Overview
2. Data Cleaning (handling duplicates & missing values)
3. Correlation Analysis
4. Data Visualization (bar plots, heatmaps, histograms)

## 📁 Dataset

The dataset used is `winequality-red.csv`, containing physicochemical test results (like acidity, sugar, pH, alcohol, etc.) and a quality score for red wine samples.

## 🚀 How to Run

1. Clone the repository
   ```bash
   git clone <your-repo-url>
   ```
2. Install the required dependencies
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Open and run the notebook `pythonproject.ipynb` in Jupyter Notebook / Google Colab

## 📈 Sample Insights

- Correlation heatmap highlights which physicochemical features are most related to wine quality
- Quality score distribution shows a visible class imbalance
- Feature histograms give a quick look at the spread and skewness of each variable

## 📄 License

This project is open-source and available for learning and personal use.
