# Week 5: Multiple Discriminant Analysis (MDA)

## 📖 Overview
In Week 5, the focus was on understanding the differences between **Multiple Regression Analysis** and **Multiple Discriminant Analysis (MDA)**, followed by applying **Linear Discriminant Analysis (LDA)** to the HBAT dataset. 
The assignment included defining variable types, constructing discriminant functions and evaluating classification performance on both training and test data.

---

## 🧩 1. Multiple Regression vs Multiple Discriminant Analysis

### Multiple Regression Analysis
- Models the relationship between a **single dependent variable** and multiple independent variables.  
- Used to **predict continuous outcomes**.  
- Provides insights into the **strength and direction** of predictors.  
- Helps in quantifying how each explanatory factor affects the response.  
- Example: Predicting **customer satisfaction score** from factors like product quality, price, and service:contentReference[oaicite:1]{index=1}.

### Multiple Discriminant Analysis (MDA)
- Used for **classification** into **predefined groups** based on predictors.  
- Builds **discriminant functions** (linear combinations of variables) that separate groups.  
- Produces **canonical coefficients** for classification.  
- Sensitive to **outliers** and requires sufficient sample size per group.  
- Also known as **Canonical Variates Analysis** or **Canonical Discriminant Analysis**.  
- Example: Classifying **regions** of customers based on product/service attributes.
---

## 📊 2. HBAT Dataset Variables
For this assignment, **X4** is the **non-metric variable (grouping)** and variables **X6–X18** are the **metric predictors**:

| Variable | Type       | Description                       |
|----------|-----------|------------------------------------|
| X4       | Non-Metric| Region                             |
| X6       | Metric    | Product Quality                    |
| X7       | Metric    | E-commerce Activities / Websites   |
| X8       | Metric    | Technical Support                  |
| X9       | Metric    | Complaint Resolution               |
| X10      | Metric    | Advertising                        |
| X11      | Metric    | Product Line                       |
| X12      | Metric    | Sales Force Image                  |
| X13      | Metric    | Competitive Pricing                |
| X14      | Metric    | Warranty & Claims                  |
| X15      | Metric    | New Products                       |
| X16      | Metric    | Ordering & Billing                 |
| X17      | Metric    | Price Flexibility                  |
| X18      | Metric    | Delivery Speed                     |

- **Number of Groups in X4:** 2 (e.g., two regions/customers classes).  

---

## 🧮 3. Linear Discriminant Function (LDF)
- Constructed using **X6–X18** as predictors.  
- The function maximizes separation between the **two groups** defined by X4.  
- Each case is scored based on the LDF, and the higher score determines classification.

---

## 📈 4. Classification Results

### a. Training Data (HBAT)
- Built the discriminant model on training set.  
- Produced a **confusion matrix** showing actual vs predicted groups.  
- Identified **misclassified observations**.  
- Calculated the **misclassification probability (error rate)**.  

### b. Test Data (HBAT_Test)
- Applied the LDF on test set.  
- Produced a **confusion matrix** for test results.  
- Reported **misclassified cases** and the **overall error rate**.  

---

## 💡 Learnings
- **Regression vs Discriminant Analysis**: regression predicts continuous values, while discriminant analysis classifies into groups.  
- **Discriminant functions** are powerful in classification tasks, but sensitive to outliers.  
- Classification accuracy is best evaluated using **confusion matrices** and **error probabilities**.  
- Testing on independent data (HBAT_Test) validates model generalizability.  

---

## 📂 Files in This Folder
- `Assignment 5.pdf` – Original assignment questions & responses.  
- `HBAT.csv` – Training dataset  
- `HBAT_Test.csv` – Test dataset  
- `analysis.ipynb` – Python/R notebook for LDA and confusion matrices  
---
