# Week 3: Exploratory Factor Analysis (EFA)

## 📖 Overview
In Week 3, the focus was on **Factor Analysis** — a multivariate statistical method used to reduce data dimensionality and identify latent constructs behind observed variables. 
I explored **scree plots**, **eigenvalues** and **factor patterns** using the HBAT dataset.

---

## 🧩 1. Scree Plot
- The **scree plot** is used to decide the number of factors to retain.  
- The point where the curve shows a sudden break (the “elbow”) indicates the number of significant factors.  
- From the provided scree plot, the curve breaks around the **5th factor**, suggesting **5 factors** should be retained. 

---

## 📊 2. Eigenvalues
- Factors with eigenvalues **greater than 1.0** are considered meaningful.  
- In our case, the eigenvalues were:  
  1. 3.567  
  2. 2.998  
  3. 1.738  
  4. 1.287  
  5. 1.005  
- Since **5 values are > 1.0**, we again confirm that **5 factors** should be retained.  

---

## 📈 3. Factor Pattern & Variable Assignment
- Factor loadings were examined with thresholds of **0.5 and 0.6**.  
- Example assignments (with 0.6 threshold):  
  - **Factor 1**: X18, X9, X16, X15, X12, X10  
  - **Factor 2**: X6, X11, X8, X14  
  - **Factor 3**: X18, X9, X16, X13, X17, X12, X7, X10  

### Issues Observed
- Some variables cross-loaded (appeared in multiple factors).  
- Solution: Adjusting the **loading cutoff** (e.g., 0.5 vs 0.6) or applying **rotation methods** (varimax, oblimin) to achieve clearer separation.

---

## 📂 4. HBAT Dataset (X6–X18, excluding X15 & X17)
- **Scree Plot** → suggested **5 factors**.  
- **Eigenvalues** → suggested **4 factors**.  
- **Factor Pattern** → grouped variables differently depending on the threshold.
  

### Challenges & Fixes
- **Inconsistent variable grouping** due to cross-loadings.  
- **Resolution**: Use factor rotation, experiment with different cutoff thresholds and interpret factors based on theory as well as statistics.

---

## 💡 Learnings
- The **scree plot** and **eigenvalue > 1 rule** are both critical for factor determination.  
- Factor loadings are sensitive to the chosen cutoff, which can cause overlaps.  
- Factor rotation improves interpretability.  
- Practical application on HBAT data showed how different methods can lead to slightly different conclusions.  

---

## 📂 Files in This Folder
- `Week 3.pdf` – Assignment  
- `Screenshot_FactorAnalysis.jpg` – Scree plot, variance explained and factor pattern output  

