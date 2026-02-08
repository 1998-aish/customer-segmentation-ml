# Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project focuses on segmenting customers based on their behavior using unsupervised machine learning. The goal is to identify distinct customer groups to support business decision-making and targeted marketing strategies.

---

## 📊 Dataset
- **Source:** Mall Customers Dataset (Kaggle)
- **Features Used:**
  - Age
  - Annual Income (k$)
  - Spending Score (1–100)

CustomerID and Gender were excluded to avoid non-behavioral bias.

---

## ⚙️ Methodology
1. Data loading and exploration
2. Feature selection
3. Feature scaling using StandardScaler
4. K-Means clustering
5. Cluster interpretation
6. Visualization of results
7. PCA for dimensionality reduction and visualization

---

## 🔍 Clustering Results
Customers were segmented into **three clusters**:

- **Cluster 0:** Older customers with moderate income and low spending behavior
- **Cluster 1:** High-income, high-spending premium customers
- **Cluster 2:** Younger customers with lower income but moderate spending, indicating future potential

---

## 📈 Visualizations
### Income vs Spending
![Income vs Spending](images/clusters.png)

### PCA Visualization
PCA was used to project customer data into two dimensions for better visualization of cluster separation.

---

## 🧠 Key Insights
- High-income customers are not always high spenders
- Younger customers show strong spending potential despite lower income
- Customer segmentation enables targeted marketing and personalized offers

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- PCA
- K-Means Clustering

---

## 🚀 Future Improvements
- Experiment with different K values
- Add Silhouette Score for cluster validation
- Include Gender as an optional feature
- Apply the approach to larger real-world datasets
