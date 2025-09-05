# Abalone Age Detection  

This project predicts the **age of abalone (a type of marine mollusk)** using physical measurements such as length, diameter, height, and weight. The dataset comes from the UCI Machine Learning Repository:  
http://archive.ics.uci.edu/ml/datasets/abalone  

---

## 📌 Project Overview  

- **Objective:** Estimate abalone age based on physical features.  
- **Feature Engineering:** Age is derived from the formula:  
                        Age (years)=Rings+1.5



- **Analysis:**  
- Explored correlations between features  
- Detected and visualized outliers  
- **Models Implemented:**  
- Logistic Regression  
- Support Vector Machine (SVM)  
- Linear Regression  

---

## 📊 Dataset  

- **Source:** UCI Abalone Dataset  
- **Attributes:**  
- Sex (M/F/I)  
- Length, Diameter, Height  
- Whole weight, Shucked weight, Viscera weight, Shell weight  
- Rings (used to calculate Age)  

---

## ⚙️ Steps in the Notebook  

1. **Data Loading & Cleaning**  
 - Read dataset, assigned column names  
 - Derived new target variable: *Age*  

2. **Exploratory Data Analysis (EDA)**  
 - Univariate analysis of features  
 - Correlation study (linear & non-linear relationships)  
 - Outlier detection  

3. **Model Building**  
 - Logistic Regression for classification  
 - SVM for improved decision boundaries  
 - Linear Regression for continuous age prediction  




