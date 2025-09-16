# Week 6: Logistic Regression

## 📖 Overview
In Week 6, I studied **Logistic Regression** in comparison with **Linear Regression** and **Linear Discriminant Analysis (LDA)**. 
The assignment involved building **binary logistic regression models** using the HBAT dataset.
Applying both **forward selection** and **backward elimination** and comparing their performance using the **ROC curve** and **Area Under the Curve (AUC)**.

---

## 🧩 1. Logistic Regression vs Other Methods

### Logistic Regression
- Predicts **binary or categorical outcomes** (e.g., yes/no, 0/1).  
- Models the **probability of an event** given independent variables.  
- Does not assume a linear relationship between dependent and independent variables.  
- Evaluated using **ROC curves** and **AUC**.  

### Linear Regression
- Predicts **continuous dependent variables** from independent predictors.  
- Assumes a **linear relationship** between dependent and independent variables.  
- Widely used due to simplicity and interpretability.  
- Not suitable for categorical dependent variables.  

### Linear Discriminant Analysis (LDA)
- Used to **separate two or more groups** of observations.  
- Predicts categorical grouping based on several independent variables.  
- Assumes linearity but is more sensitive to outliers and group size imbalances.  

---

## 📊 2. HBAT Dataset Setup
- **Dependent Variable (non-metric):** X4 (Region → coded into binary groups)  
- **Independent Variables (metric):** X6 – X15.

---

## 🧮 3. Forward Selection Binary Logistic Regression
- Applied with **significance level = 0.05**.  
- At each step, the most significant variable is entered into the model.  
- After each step, the **summary, ROC curve, and AUC** were reported.  

### Results
- Final AUC: **0.9676**  
- Indicates a **very strong model** with high discriminatory power.

---

## 📈 4. Backward Elimination Binary Logistic Regression
- Started with all variables (X6–X15).  
- At each step, the **least significant variable** (p > 0.05) was removed.  
- After each elimination, the **summary, ROC curve and AUC** were recalculated.  

### Results
- Final AUC: **0.9651**  
- Still very strong, but slightly lower than forward selection.
---

## ⚖️ 5. Model Comparison
- **Forward Selection AUC:** 0.9676  
- **Backward Elimination AUC:** 0.9651  

✅ Both models are good (AUC > 0.9).  
🏆 **Forward Selection is slightly better** due to the higher AUC score.  

---

## 💡 Learnings
- Logistic Regression is the preferred method for **binary classification problems**.  
- **Forward Selection** tends to build more optimal models when strong predictors exist.  
- **ROC and AUC** are critical metrics for evaluating classification performance.  
- Comparing methods ensures model robustness and avoids overfitting.  

---

## 📂 Files in This Folder
- `Assignment 6.pdf` – Original assignment  
- `HBAT.csv` – Training dataset  
- `analysis.ipynb` – Python/R notebook for logistic regression, ROC curves and variable selection  

---
