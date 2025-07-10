

#  Customer Segmentation using K-Means Clustering

This project applies **unsupervised machine learning** (K-Means Clustering) to segment customers based on their behavioral patterns. The goal is to help businesses personalize marketing strategies by identifying groups like **high-value customers**, **frequent buyers**, or **deal seekers**.

---

##  Features

- Data preprocessing and feature scaling  
- Elbow method to determine optimal clusters  
- K-Means clustering for customer segmentation  
- Visualizations: pair plots, cluster heatmaps, segment profiles  
- (Optional) Power BI dashboard to present cluster insights

---

##  Dataset

- Source: [Mall Customer Dataset](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial)
- Fields:
  - `CustomerID`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1–100)`
  - `Gender` *(optional for clustering)*

---

##  Clustering Process

1. **Import & Explore** the dataset  
2. **Scale** relevant features using `StandardScaler`  
3. **Find optimal `k`** using the Elbow Method  
4. **Train** KMeans model with selected `k`  
5. **Label** and analyze cluster profiles  
6. **Visualize** using scatter plots and pair plots  
7. *(Optional)* Export cluster-labeled data to Power BI

---

##  Visualizations

-  Elbow Curve for K optimization  
-  2D/3D Cluster Plots  
-  Spending vs Income per segment  
-  (Optional) Power BI Dashboard for segment drill-down

---

##  Tech Stack

- **Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Optional**: Power BI, Plotly

---

##  Use Cases

- Retail customer profiling  
- Marketing campaign targeting  
- Personalized recommendations  
- Customer loyalty programs

---


