# 💼 Insurance Customer Segmentation using Clustering

---

![Project Thumbnail](customer-segmentation.png)

---

## 📌 Project Overview

This project performs **customer segmentation** for an insurance dataset using **unsupervised machine learning** techniques — primarily **K-Means**, **Agglomerative Hierarchical Clustering**, and **DBSCAN**.

The goal is to uncover **natural customer groups** based on behavioral and financial attributes, enabling **targeted marketing**, **personalized offers**, and **risk-based policy recommendations**.

**Key Objectives:**

1. **Exploratory Data Analysis (EDA):**

   * Visualize distributions, correlations, and relationships between key variables using histograms, pairplots, and heatmaps.
2. **Cluster Modeling:**

   * Apply **K-Means**, **Agglomerative Clustering**, and **DBSCAN**.
   * Experiment with multiple linkage methods and distance metrics.
3. **Model Evaluation:**

   * Compare cluster quality using **Silhouette Scores** and visualizations.
4. **Business Insights:**

   * Interpret the best-performing model and derive actionable insurance marketing strategies.

---

## 🛠 Technologies & Libraries

* **Python 3**
* **Pandas, NumPy** – Data manipulation
* **Scikit-learn** – Clustering & evaluation (K-Means, Agglomerative, DBSCAN, Silhouette Score)
* **Matplotlib, Seaborn** – Data visualization
* **SciPy** – Dendrograms for hierarchical clustering

---

## 📊 Visualizations

* **Histograms & Boxplots** – Distribution of financial attributes
* **Correlation Heatmap** – Feature relationships
* **Pairplots** – Multi-dimensional feature comparison
* **Dendrograms** – Hierarchical cluster structure
* **Cluster Plots & Bar Charts** – Algorithm comparison and cluster insights

---

## 🧠 Cluster Insights

* **Agglomerative (Single–Manhattan)** performed best with the highest **Silhouette Score (~0.286)**.
* Clear segmentation into **low**, **medium**, and **high engagement** customers.
* Patterns reveal which customers are more likely to purchase premium policies versus those needing reactivation offers.

---

## 💼 Business Applications

* Identify **premium** customers for high-value insurance plans.
* Target **low-engagement** customers with reactivation campaigns.
* Use clustering to enhance **marketing efficiency** and **policy personalization**.

---

## 📈 Results Summary

| Algorithm         | Parameters       | Silhouette Score | Notes                         |
| ----------------- | ---------------- | ---------------- | ----------------------------- |
| **Agglomerative** | Single–Manhattan | **0.286**        | Best overall segmentation     |
| **K-Means**       | k=2              | 0.232            | Simple two-tier grouping      |
| **DBSCAN**        | —                | 0.000            | No meaningful clusters formed |

---


## 🤝 Connect

- [LinkedIn](https://www.linkedin.com/in/varsha-shekhar)
- [Gmail](varshaiyer96@gmail.com)
