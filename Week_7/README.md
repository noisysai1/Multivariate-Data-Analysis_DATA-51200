# Week 7: MANOVA & ANOVA

## 📖 Overview
In Week 7, we studied **Multivariate Analysis of Variance (MANOVA)** and **Analysis of Variance (ANOVA)**.  
Due to software limitations in SAS  (GUI version not supporting MANOVA), the assignment focused on **ANOVA** using the **HBAT200.sav** dataset.
The task involved reproducing **Tables 5, 6, 7** and **Figure 6** from the reference material (Tables.pdf)

---

## 🧩 1. ANOVA vs MANOVA
- **ANOVA (Analysis of Variance)**:  
  - Tests for differences in **means** of a dependent variable across groups.  
  - One dependent variable at a time.  
  - Useful for identifying whether group means differ significantly.  

- **MANOVA (Multivariate Analysis of Variance)**:  
  - Extension of ANOVA to handle **multiple dependent variables simultaneously**.  
  - Evaluates whether mean vectors differ across groups.  
  - Provides richer insights but requires specialized software support.  

---

## 📊 2. HBAT200.sav Dataset
- The dataset was used to replicate statistical outputs.  
- Dependent and independent variables were tested using ANOVA to generate summary tables, Bartlett’s test, and visual plots.  

---

## 📈 3. Reproduced Outputs
### Table 5
- ANOVA summary table comparing group means.  
- Includes **Sum of Squares, Degrees of Freedom (df), Mean Squares, F-values, and p-values**.  

### Table 6
- Expanded ANOVA with more detail on group effects.  

### Bartlett’s Test
- Tested the **homogeneity of variances assumption**.  
- Bartlett’s test checks if variances are equal across groups (key requirement for ANOVA).  

### Figure 6
- Graphical representation (likely a **means plot** or **interaction plot**) showing group differences visually.  

### Table 7
- Further statistical breakdown (likely post-hoc comparisons or multiple ANOVA results).  
---

## 💡 Learnings
- ANOVA helps determine if **group differences exist** for one dependent variable.  
- MANOVA extends the concept to **multiple dependent variables**, giving a fuller multivariate perspective.  
- Assumptions (like **equal variances**) must be tested (e.g., using Bartlett’s test).  
- Graphical outputs (like means plots) support interpretation of statistical results.  
- Practical limitation: software tools sometimes restrict methods, requiring adjustments in analysis.  

---

## 📂 Files in This Folder
- `Assignment 7.pdf` – Original assignment write-up:contentReference[oaicite:2]{index=2}  
- `HBAT200.sav` – Dataset used for ANOVA/MANOVA analysis  
- `Tables.pdf` – Reference for reproducing Tables 5, 6, 7 and Figure 6  
- `analysis.ipynb` – Python/R notebook (ANOVA replication)  

---
