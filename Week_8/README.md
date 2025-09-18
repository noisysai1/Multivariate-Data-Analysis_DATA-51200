# Week 8: K-Means Clustering

## 📖 Overview
In Week 8, I studied **K-means clustering**, one of the most widely used unsupervised learning algorithms.  
The assignment required summarizing the steps of K-means, discussing advantages and limitations and applying.
The algorithm on the HBAT dataset with **3, 4, and 5 clusters** using the **Euclidean distance measure**.

---

## 🧩 1. Understanding K-Means Clustering

### What is Clustering?
- **Clustering** is the process of grouping objects based on shared characteristics.  
- Goal: maximize **similarity within clusters** and minimize **similarity across clusters**.

### K-Means Algorithm Steps
1. Select **K initial cluster centers** (centroids).  
2. Assign each data point to the **nearest cluster center**.  
3. Recalculate each cluster’s centroid as the mean of its assigned points.  
4. Repeat steps 2–3 until centroids stabilize (no significant changes).  

### Example
- Dataset of cricket players with attributes like **score** and **income**.  
- K-means groups players into performance tiers based on similarities.  

---

## ✅ 2. Advantages of K-Means
- Easy to implement and interpret.  
- Scales well for **large datasets**.  
- Produces clusters that are intuitive to analyze. 

## ⚠️ 3. Disadvantages
- Sensitive to **initialization** (results vary depending on chosen centroids).  
- Assumes clusters are **spherical and equally sized** (not always realistic).  
- Strongly affected by **outliers**.  

## 🚫 4. Limitations
- Performs poorly with **categorical/non-numeric data**.  
- Requires pre-specifying **K (number of clusters)**.  

---

## 📊 5. HBAT Dataset Clustering

### Variables Used
- X6 (Product Quality)  
- X8 (Technical Support)  
- X12 (Sales Force Image)  
- X15 (New Products)  
- X18 (Delivery Speed) 

### a. 3 Clusters
- Generated statistics for means, standard deviations, and distances between centroids.  
- Cluster sizes reported.  
- Clusters showed meaningful separation but some overlap.  

### b. 4 Clusters
- Improved separation compared to 3 clusters.  
- Better distribution of observations across clusters.  
- Centroid distances indicated more distinct grouping.  

### c. 5 Clusters
- More granularity but slightly fragmented results.  
- Some clusters became too small, reducing interpretability.  

### Best Result
- **4 clusters** provided the most balanced and interpretable results.  
- Clear separation and meaningful business insights without excessive fragmentation.  

---

## 💡 Learnings
- K-means is effective for **partitioning continuous data**.  
- Choosing the right **number of clusters** (K) is critical.  
- Evaluating results requires examining:  
  - **Cluster means & standard deviations**  
  - **Distances between centroids**  
  - **Observation counts per cluster**  
- Business interpretation of clusters is as important as statistical validation.  

---

## 📂 Files in This Folder
- `Assignment 8.pdf` – Original assignment write-up.  
- `HBAT.csv` – Dataset used for clustering  
- `analysis.ipynb` – Python/R notebook for K-means clustering with 3, 4, 5 clusters  

---
