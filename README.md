# Multivariate-Data-Analysis_DATA-51200

# DATA-51200 Multivariate Data Analysis – 8 Week Summary

## 📖 Course
This course introduced key statistical methods for analyzing **multivariate data**. Across 8 weeks, 
I explored both the **theoretical foundations** and **practical applications** of advanced statistical techniques using the HBAT dataset and other examples.  

---

## 🗓️ Week-by-Week Learnings

### Week 1: Introduction & Dataset Familiarization
- Learned the structure of **multivariate datasets** (e.g., HBAT with X1–X23 variables).  
- Explored categorical vs continuous variables.  
- Understood why **preprocessing** (missing data handling, scaling) is crucial before modeling.  

---

### Week 2: Missing Data & Exploratory Visualizations
- Studied causes of **missing data** (technical errors, survey non-responses, equipment failures).  
- Learned methods: **deletion, imputation, modeling**.  
- Created **histograms** with normal curve overlays (X6, X7, X16, X17).  
- Generated **scatterplots** (X7 vs X19, X6 vs X19).  
- Conducted **normality checks** on X1 and X2.  

---

### Week 3: Exploratory Factor Analysis (EFA)
- Applied **scree plots** and **eigenvalue > 1 rule** to determine number of factors.  
- Learned how **factor loadings** assign variables to latent constructs.  
- Identified **cross-loading issues** and explored **rotation methods** (varimax, oblimin).  
- Applied factor analysis on HBAT variables X6–X18 (excluding X15, X17).  

---

### Week 4: Multiple Linear Regression
- Built regression models with continuous dependent variables.  
- Calculated **residuals** and model accuracy using **RMSE**.  
- Modeled **X19** using predictors (X6, X7, X9, X11, X12, X16).  
- Compared **full vs reduced models** after removing weak predictors.  
- Learned the trade-off between **model complexity vs interpretability**.  

---

### Week 5: Multiple Discriminant Analysis (MDA)
- Compared **Multiple Regression** vs **Discriminant Analysis**.  
- Regression: predicts continuous outcomes.  
- Discriminant: classifies observations into **predefined groups**.  
- Applied **Linear Discriminant Function (LDF)** using HBAT (X6–X18 vs grouping variable X4).  
- Evaluated results using **confusion matrices** and **misclassification error rates** on both training and test data.  

---

### Week 6: Logistic Regression
- Compared **Logistic Regression**, **Linear Regression**, and **LDA**.  
- Logistic Regression: models **binary outcomes** (probabilities).  
- Applied **forward selection** and **backward elimination** logistic regression on HBAT.  
- Evaluated models with **ROC curves** and **AUC values**.  
- Forward selection (AUC = 0.9676) slightly outperformed backward elimination (AUC = 0.9651).  

---

### Week 7: MANOVA & ANOVA
- Learned differences between **ANOVA** (1 DV) and **MANOVA** (multiple DVs).  
- Due to SAS UE limitations, focused on ANOVA using HBAT200.sav.  
- Reproduced **ANOVA summary tables**, **Bartlett’s test**, and **means plots**.  
- Bartlett’s test was used to check **homogeneity of variances assumption**.  
- Reinforced how to interpret F-statistics and p-values.  

---

### Week 8: K-Means Clustering
- Learned steps of **K-means clustering**:
  1. Initialize K cluster centers.  
  2. Assign points to nearest centroid.  
  3. Recalculate centroids.  
  4. Repeat until stable.  
- Applied clustering on HBAT variables (X6, X8, X12, X15, X18).  
- Compared solutions for **3, 4, and 5 clusters**:
  - 3 clusters: broad grouping, but some overlap.  
  - 4 clusters: best separation and interpretability.  
  - 5 clusters: too fragmented.  
- Learned **advantages** (simplicity, scalability) and **limitations** (sensitivity to outliers, poor fit for categorical data).  

---

## 🌟 Key Takeaways
- **Data preparation** (cleaning, missing data handling, normality checks) is foundational.  
- **Dimensionality reduction** (Factor Analysis) reveals hidden structures.  
- **Regression models** (linear, logistic) predict outcomes with measurable accuracy.  
- **Classification techniques** (Discriminant, Logistic Regression) separate groups effectively.  
- **ANOVA/MANOVA** test differences across groups.  
- **Clustering** identifies natural groupings without predefined labels.  
- Model evaluation metrics (**RMSE, SEE, ROC, AUC, confusion matrix**) are critical to judge performance.  

---

## 📂 Repository Structure
- `Week1/` – Dataset overview & intro notes  
- `Week2/` – Missing data, histograms, scatterplots  
- `Week3/` – Factor analysis (scree plots, eigenvalues, patterns)  
- `Week4/` – Multiple regression models & evaluation  
- `Week5/` – Discriminant analysis & classification results  
- `Week6/` – Logistic regression & ROC curve analysis  
- `Week7/` – ANOVA tables & Bartlett’s test  
- `Week8/` – K-means clustering (3, 4, 5 clusters)  
- `Course_Summary.md` – This file  

---

## 🧑‍🎓 Author
**Sai Kumar Murarishetti**  
Master’s in Data Science   
Lewis University  
