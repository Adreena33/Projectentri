# 📌 Project Overview

This project focuses on building a machine learning classification model to predict whether an individual's income exceeds $50K per year using census data. This is a **binary classification** problem based on demographic, educational, and financial features.

---

## 📊 Dataset Information

- **Dataset Name**: Adult Income Dataset (Census Income Dataset)  
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/20/census+income)  
- **Total Records**: ~48,842 entries  
- **Features**: 14 input features + 1 target variable  
- **Target Variable**: `income` (`<=50K` or `>50K`)  

### 🔍 Feature Categories

- **Demographic**: `age`, `sex`, `race`, `native-country`  
- **Education**: `education`, `education-num`  
- **Employment**: `workclass`, `occupation`, `hours-per-week`  
- **Financial**: `capital-gain`, `capital-loss`, `fnlwgt`  
- **Other**: `relationship`, `marital-status`

---

## ⚙️ Installation & Requirements

Make sure you have Python 3.7+ installed.

### 🔧 Required Libraries

Install the dependencies using:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

Or use a `requirements.txt`:

```txt
pandas
numpy
scikit-learn
matplotlib
seaborn
```

---

## 🚀 Running the Project

### Step 1: Load and Explore the Dataset
- Load data from UCI repository or CSV
- Check for nulls, duplicates, and data types

### Step 2: Preprocess the Data
- Handle missing values
- Remove outliers using IQR method
- Encode categorical columns
- Scale numerical features


