# 🛒 SmartCart Customer Clustering System

## 📌 Project Overview
SmartCart Customer Clustering System is an unsupervised machine learning project designed to segment customers based on purchasing behavior, engagement levels, and demographic information.  

The goal is to uncover hidden customer patterns and enable personalized marketing, improved retention strategies, and early churn detection.

---

## 🎯 Problem Statement
SmartCart is an e-commerce platform serving customers across multiple countries.  
Currently, marketing strategies are generic and not tailored to different customer behaviors.  

This leads to:
- Inefficient marketing campaigns
- Missed opportunities to retain high-value customers
- Delayed identification of churn-prone users

To solve this, we build an intelligent customer segmentation system using clustering algorithms.

---

## 📊 Dataset Description

The dataset contains:
- **2240 customer records**
- **22 features**

### 1️⃣ Customer Demographics
- ID
- Year_Birth
- Education
- Marital_Status
- Income
- Kidhome
- Teenhome
- Dt_Customer

### 2️⃣ Purchase Behavior (Spending)
- MntWines
- MntFruits
- MntMeatProducts
- MntFishProducts
- MntSweetProducts
- MntGoldProds

### 3️⃣ Purchase Behavior (Frequency)
- NumDealsPurchases
- NumWebPurchases
- NumCatalogPurchases
- NumStorePurchases
- NumWebVisitsMonth

### 4️⃣ Customer Feedback & Activity
- Recency
- Complain

---

## 🧠 Machine Learning Approach

- Data Cleaning & Preprocessing
- Feature Engineering
- Scaling using StandardScaler
- Dimensionality Reduction (PCA)
- Clustering Algorithms:
  - K-Means
  - Hierarchical Clustering
  - DBSCAN (optional comparison)

---

## 📈 Expected Outcomes

- Meaningful customer segments
- Identification of high-value customers
- Early churn risk detection
- Data-driven marketing strategies
- Improved business decision-making

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🚀 How to Run

```bash
# Clone the repository
git clone <repository-url>

# Install dependencies
pip install -r requirements.txt

# Run the notebook or script
python main.py
