

---

# 🛒 SmartCart – Intelligent Customer Segmentation System

> Unsupervised Machine Learning Project for Data-Driven Customer Clustering

---

## 📌 Project Overview

**SmartCart** is a growing e-commerce platform serving customers across multiple countries. The company collected data for **2240 customers with 22 attributes**, including demographics, purchase behavior, website activity, and customer feedback .

Currently, SmartCart uses **generic marketing and engagement strategies** for all customers, leading to:

* Inefficient marketing spend
* Missed opportunities to retain high-value customers
* Delayed identification of churn-prone users 

To address this, this project builds an **Intelligent Customer Segmentation System** using **unsupervised machine learning (clustering algorithms)** to group customers into meaningful clusters based on behavioral and transactional patterns .

---

## 🎯 Business Objective

Develop a data-driven segmentation system that:

* Identifies distinct customer groups
* Enables personalized marketing strategies
* Improves customer retention
* Optimizes campaign targeting
* Supports strategic business decision-making

---

## 📊 Dataset Description

Each row represents a **customer** with demographic, behavioral, and engagement attributes .

### 1️⃣ Customer Demographics

* `ID` – Unique customer identifier
* `Year_Birth` – Birth year
* `Education` – Highest education level
* `Marital_Status` – Marital status
* `Income` – Yearly household income
* `Kidhome` – Number of small children
* `Teenhome` – Number of teenagers
* `Dt_Customer` – Enrollment date

### 2️⃣ Purchase Behavior (Amount Spent)

* `MntWines`
* `MntFruits`
* `MntMeatProducts`
* `MntFishProducts`
* `MntSweetProducts`
* `MntGoldProds` 

### 3️⃣ Purchase Behavior (Frequency)

* `NumDealsPurchases`
* `NumWebPurchases`
* `NumCatalogPurchases`
* `NumStorePurchases`
* `NumWebVisitsMonth` 

### 4️⃣ Customer Feedback

* `Recency` – Days since last purchase
* `Complain` – Complaint in last 2 years (1 = Yes, 0 = No) 

---

## 🧠 Machine Learning Approach

### 1️⃣ Data Preprocessing

* Handling missing values
* Feature transformation
* Encoding categorical variables
* Date feature extraction (customer tenure)
* Feature scaling using StandardScaler

### 2️⃣ Feature Engineering

* Total Spending calculation
* Purchase frequency score
* Loyalty indicators
* Customer tenure calculation

### 3️⃣ Clustering Algorithms Implemented

* K-Means Clustering
* Hierarchical Clustering (Optional)
* DBSCAN (Optional experimentation)

### 4️⃣ Cluster Validation Techniques

* Elbow Method (WCSS)
* Silhouette Score
* Cluster Profiling (Mean Feature Comparison)

---

## 📈 Business Impact

The segmentation model enables:

* 🎯 Targeted marketing campaigns
* 💎 Identification of high-value customers
* ⚠️ Early detection of churn-risk customers
* 📊 Optimized promotional strategies
* 💰 Increased ROI on marketing spend

---

## 🛠️ Tech Stack

* **Python**
* **Pandas & NumPy**
* **Scikit-Learn**
* **Matplotlib & Seaborn**
* Jupyter Notebook

---

## 📂 Project Structure

```
SmartCart-Clustering-System/
│
├── data/
│   └── customer_data.csv
│
├── notebooks/
│   └── clustering_analysis.ipynb
│
├── models/
│   └── kmeans_model.pkl
│
├── src/
│   ├── preprocessing.py
│   ├── clustering.py
│   └── evaluation.py
│
└── README.md
```

---

## 🚀 How to Run

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/SmartCart-Clustering-System.git
cd SmartCart-Clustering-System
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Notebook

```bash
jupyter notebook
```

---

## 📊 Sample Insights (Example Cluster Types)

* 🟢 High-Spending Loyal Customers
* 🟡 Discount-Oriented Buyers
* 🔵 Web-Active Browsers
* 🔴 Low-Engagement / Churn-Risk Customers

---

## 🔮 Future Enhancements

* Deploy interactive dashboard (Streamlit / Power BI)
* Integrate real-time customer scoring
* Add Recommendation Engine
* Implement RFM-based advanced segmentation
* Deploy model as REST API

---

## 👨‍💻 Role

Developed as an **AI/ML Engineer**, focusing on clustering algorithms and data-driven customer behavior analysis .



* 🔥 Make this recruiter-optimized (for ML Engineer roles)
* 📊 Add model performance visual explanation section
* 🌐 Create a Streamlit deployment version
* 📄 Generate a complete project report (DOC/PDF format)

Tell me what you want next 🚀
