# Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project performs **Customer Segmentation** using **Machine Learning (K-Means Clustering)** on an online retail dataset. The goal is to group customers based on their purchasing behavior using **RFM Analysis (Recency, Frequency, Monetary Value)**.

Customer segmentation helps businesses:
- Identify premium customers
- Find inactive customers
- Improve marketing strategies
- Increase customer retention
- Build personalized recommendations

---

# 🚀 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 📂 Dataset
Dataset used:
- Online Retail Dataset

Main features used:
- CustomerID
- InvoiceDate
- Quantity
- UnitPrice
- TotalAmount

---

# 🧠 Machine Learning Technique
## K-Means Clustering
K-Means is an unsupervised machine learning algorithm used to divide customers into groups based on similar behavior.

This project uses:
- K-Means Clustering
- StandardScaler
- PCA (Principal Component Analysis)
- RFM Analysis

---

# 📊 RFM Analysis
The project calculates:

| Feature | Description |
|---|---|
| Recency | How recently a customer purchased |
| Frequency | How often the customer purchases |
| Monetary | How much money the customer spends |

These values are used to create customer segments.

---

# ⚙️ Project Workflow
1. Import libraries
2. Load dataset
3. Data cleaning
4. Feature engineering
5. Perform RFM analysis
6. Scale features using StandardScaler
7. Find optimal clusters using:
   - Elbow Method
   - Silhouette Score
   - Davies-Bouldin Score
   - Calinski-Harabasz Score
8. Train K-Means model
9. Visualize clusters using PCA
10. Analyze customer segments

---

# 📈 Model Evaluation
The project evaluates clustering quality using:

- WCSS (Elbow Method)
- Silhouette Score
- Davies-Bouldin Index
- Calinski-Harabasz Score

---

# 🎨 Data Visualization
The project includes:
- Cluster visualization
- 2D PCA visualization
- 3D PCA visualization
- Customer segment analysis charts

---
# ▶️ How to Run the Project
## 1. Clone Repository
```bash
git clone <your-repository-link>
```

## 2. Install Requirements
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 3. Run Notebook
Open:
```bash
customer_segmantation.ipynb
```

Run all cells.

---

# 🔥 Future Improvements
- Build a Streamlit web application
- Add Deep Learning models
- Deploy project online
- Real-time customer analysis
- Add recommendation system

---

# 📌 Results
The model successfully groups customers into meaningful segments based on shopping behavior. Businesses can use these insights to improve marketing and customer engagement.

---

# 🙌 Author
Developed by Indunil

