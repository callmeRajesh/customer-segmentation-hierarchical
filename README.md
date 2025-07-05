# 📊 Customer Segmentation Using Hierarchical Clustering

This project applies **Hierarchical Clustering** (unsupervised machine learning) to group customers based on how often they visit a store and how much they spend. The goal is to discover natural customer segments for business insights.

---

## 🔍 Dataset

A synthetic dataset of 7 customers with:
- `Visits Per Week`
- `Average Spend (RM)`

---

## 🧠 Objective

To explore whether customers form natural clusters such as:
- **Loyal customers** (frequent visits, low spending)
- **Premium customers** (high spenders, few visits)
- **Mid-tier** regulars

---

## 🔧 Tools & Libraries

- Python 🐍
- Pandas
- Matplotlib
- Seaborn
- Scipy (linkage, dendrogram, fcluster)

---

## 📈 Steps Performed

1. Built a linkage matrix using `ward` method
2. Plotted a dendrogram to visualize merge distances
3. Cut the dendrogram at multiple distances (t=40, t=60)
4. Assigned cluster labels using `fcluster`
5. Visualized the customer clusters in a scatter plot
6. Interpreted the customer behavior per cluster

---

## 📊 Visuals

- Dendrogram with annotated cut heights
- Clustered scatter plot showing customer groups

---

## 🧩 Business Insights

- Customers can be grouped based on loyalty vs value.
- Businesses can target promotions and rewards based on cluster behavior.
- Helps in marketing segmentation and resource prioritization.
