Week 2: Missing Data & Exploratory Visualizations

## 📖 Overview
In Week 2 of DATA-51200 Multivariate Data Analysis, the focus was on understanding **missing data** and applying **exploratory visualizations** such as histograms, scatterplots and normality checks using the HBAT dataset.  

---

## 🧩 1. Missing Data
### What is Missing Data?
- Missing data occurs when values are not stored in the dataset.  
- Common causes:  
  - Technical errors  
  - Non-responses in surveys  
  - Equipment malfunction  
  - Lost or corrupted files:contentReference[oaicite:1]{index=1}

### Why it Matters
- Missing values can produce **biased and incorrect results**.  
- They may reduce accuracy, distort statistical power, and hide real relationships.

### Ways to Handle Missing Data
1. **Deletion** – remove observations with missing values (listwise/pairwise).  
2. **Imputation** – replace with estimated values (mean, median, regression).  
3. **Modeling** – predict missing values based on observed data (e.g., multiple imputation, EM algorithm).  

---

## 📊 2. Visualizations
Using the HBAT dataset:

- **Histograms (with normal curve overlay):**
  - X6  
  - X7  
  - X16  
  - X17  

- **Scatterplots:**
  - X7 vs X19  
  - X6 vs X19  

These visualizations help assess **normality** and detect **linear relationships, outliers and  patterns**.

---

## 📉 3. Normality Checks
- Hand-drawn histograms for **X1** and **X2**.  
- Scatterplot of **X1 vs X2**.  

**Findings:**  
- One variable approximates normal distribution more closely (bell-shaped).  
- Others deviate from normality, suggesting transformations or non-parametric methods may be required:contentReference[oaicite:3]{index=3}.

---

## 💡 Learnings
- Recognized the importance of **detecting and treating missing data** early.  
- Gained practice in plotting **histograms and scatterplots** to assess distributions.  
- Reinforced that **testing normality** is a prerequisite for regression, MANOVA and other multivariate models.

---

## 📂 Files in This Folder
- `Week 2 Assignment.pdf` – detailed questions & responses on missing data and plots.  
- `Results_WORK.IMPORT.pdf` – HBAT dataset used for histograms.  
- `analysis.ipynb` – Jupyter Notebook with Python visualizations.  
- `notes.md` – Summary of Week 2 learnings (this document).
