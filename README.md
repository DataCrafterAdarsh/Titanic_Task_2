# Titanic Dataset - Exploratory Data Analysis (Task 2)

This project is part of my AI/ML internship under Elevate Lab, Skill India & MSME. The goal of this task is to perform Exploratory Data Analysis (EDA) on the Titanic dataset to extract insights using Python libraries such as Pandas, Matplotlib, and Seaborn.

---

##  Task Overview

### Task Objective:
Analyze the Titanic dataset using the following EDA techniques:

---

## What I Did

### 1. Loaded & Inspected the Dataset
- Used `pandas` to load the Titanic dataset.
- Printed column names, dataset information, and summary statistics.
- Checked for missing values.

### 2. Visualized Distributions
- Plotted **histograms** of `Age` and `Fare` to understand their distributions using `seaborn.histplot`.

### 3. Created Boxplots
- Boxplot of `Age` vs `Survived`
- Boxplot of `Fare` vs `Pclass`

These helped visualize the distribution and spot outliers.

### 4. Correlation Heatmap
- Encoded categorical columns `Sex` and `Embarked`.
- Dropped unused text columns.
- Used `seaborn.heatmap` to show correlation between numerical and encoded features.

### 5. Pairplot
- Used `seaborn.pairplot()` to visualize pairwise relationships between key features:
  - `Survived`, `Age`, `Fare`, `Pclass`, `Sex`

---

##  Key Insights

- **Females** had a higher survival rate than males.
- **1st class** passengers had higher chances of survival.
- **Younger passengers** tended to survive more.
- **Fare** had a slight positive correlation with survival.

---

##  Files to Upload

- `Titanic-Dataset.csv` — Original dataset
- `task2_eda.py` — Python script with blockwise EDA
- `Pic-4,Pic-5,Pic-6,Pic-7` — Screenshots
- `README.md` — This file summarizing what was done

---

## 📅 Internship: Elevate Lab | Skill India | MSME
