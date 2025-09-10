# Week 4: Multiple Linear Regression

##  Overview
In Week 4 of DATA-51200 Multivariate Data Analysis, I explored **Linear Regression** and **Multiple Regression** models. 
The focus was on calculating regression parameters, residuals, and model accuracy using **Root Mean Square Error (RMSE)** and **Standard Error of the Estimate (SEE)**.
I also performed variable selection and compared models for accuracy.

---

##  1. Simple Linear Regression Example (By Hand)
A regression model was built using **Y (dependent variable)** and two independent variables **X1** and **X2**:

\[
Y = 0.08059 \cdot X1 - 0.16109 \cdot X2 + 5.26570
\]

### Table of Predictions & Residuals
| Actual Y | X1  | X2  | Predicted Y | Residual (Error) |
|----------|-----|-----|-------------|------------------|
| 6.0      | 6.8 | 4.7 | 5.05658     | -0.94341         |
| 3.1      | 5.3 | 5.5 | 4.80683     |  1.70683         |
| 5.8      | 4.5 | 6.2 | 4.62959     | -1.17040         |
| 4.5      | 8.8 | 7.0 | 4.84726     |  0.34726         |
| 4.5      | 6.8 | 6.1 | 4.83106     |  0.33106         |
| 3.7      | 8.5 | 5.1 | 5.12915     |  1.42915         |
| 5.4      | 8.9 | 4.8 | 5.20971     | -0.19028         |
| 5.1      | 6.9 | 5.4 | 4.95186     | -0.14811         |
| 5.8      | 9.3 | 5.9 | 5.06475     | -0.73524         |
| 5.7      | 8.4 | 5.4 | 5.07277     | -0.62723         |

### Root Mean Square Error (RMSE)
\[
RMSE = \sqrt{\frac{\sum (Residual^2)}{n}}
\]

- Total squared error = 8.4380  
- N = 10  
- RMSE = 0.9186  

 The RMSE is **low**, indicating that the model fits the data reasonably.

---

## 📊 2. Multiple Linear Regression (HBAT Dataset)

### Model Setup
Dependent Variable: **X19**  
Independent Variables: **X6, X7, X9, X11, X12, X16**

The general regression equation is:

\[
Y = B_0 + B_1(X6) + B_2(X7) + B_3(X9) + B_4(X11) + B_5(X12) + B_6(X16)
\]

---

### Accuracy Metrics
- **Coefficient of Determination (R²):** Measures the proportion of variance explained by the model.  
- **Standard Error of the Estimate (SEE):**  
\[
SEE = \sqrt{MSE}
\]  
A lower SEE indicates better model accuracy.

---

### Variable Selection
- If asked to remove two independent variables, one should analyze **p-values, multicollinearity (VIF), and correlations**.  
- Removing weaker predictors reduces noise and improves interpretability.  

---

### Reduced Model
After removing two weaker variables, the regression model becomes:

\[
Y = B_0 + B_1(X6) + B_2(X9) + B_3(X11) + B_4(X12)
\]

Comparing results:
- The reduced model may yield **slightly better SEE** and interpretability.  
- However, fewer predictors may reduce overall variance explained.  

---

## 💡 Learnings
- Regression accuracy can be measured using **RMSE** (for prediction error) and **SEE** (for model fit).  
- **Scree plots and eigenvalues** are for factor analysis, but regression focuses on **coefficients and residuals**.  
- Removing redundant or weak predictors improves simplicity without severely reducing accuracy.  
- Regression models must balance **complexity vs interpretability**.  

---

## 📂 Files in This Folder
- `Week 4.pdf` – Assignment write-up and regression tables.  
- `analysis.ipynb` – Python/R notebook for regression calculations  
- `notes.md` – Summary of Week 4.

---
