# 🛒 SmartCart Customer Clustering System

## 📌 Project Overview

SmartCart Customer Clustering System is an unsupervised machine learning project designed to segment customers based on purchasing behavior, engagement levels, and demographic information.

The goal is to uncover hidden customer patterns and enable:

- 🎯 Personalized marketing  
- 💎 High-value customer identification  
- 🔄 Improved retention strategies  
- ⚠️ Early churn detection  

---

## 🎯 Problem Statement

SmartCart is an e-commerce platform serving customers across multiple countries.  
Currently, marketing strategies are generic and not tailored to different customer behaviors.

This leads to:

- ❌ Inefficient marketing campaigns  
- ❌ Missed opportunities to retain high-value customers  
- ❌ Delayed identification of churn-prone users  

To solve this, we build an intelligent customer segmentation system using clustering algorithms.

---

## 📊 Dataset Description

The dataset contains:

- 2240 customer records  
- 22 features  

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

### 🔹 Data Cleaning & Preprocessing
- Handling missing values  
- Outlier treatment  
- Feature transformation  

### 🔹 Feature Engineering
- Total_Spend creation  
- Total_Children calculation  
- Living status categorization  

### 🔹 Feature Scaling
- StandardScaler  

### 🔹 Dimensionality Reduction
- PCA (Principal Component Analysis)  

### 🔹 Clustering Algorithms
- K-Means  
- Hierarchical Clustering  
- DBSCAN (optional comparison)  

---

## 📊 Final Cluster Summary

| Feature | Cluster 0 | Cluster 1 | Cluster 2 | Cluster 3 |
|----------|------------|------------|------------|------------|
| Income | Low (~37K) | High (~71K) | Low (~36K) | High (~70K) |
| Children | More | Fewer | More | Fewer |
| Age | ~55 yrs | ~59 yrs | ~55 yrs | ~59 yrs |
| Total Spend | Low | Very High | Low | Very High |
| Web Visits | High | Low | High | Low |
| Store/Catalog Purchase | Low | High | Low | High |
| Response Rate | Very Low (7%) | Moderate (15%) | Moderate (13%) | Best (32%) |
| Living Status | With Partner | With Partner | Alone | Alone |

---

## 🎯 Business Interpretation

### 🔵 Cluster 0 – Low Income Family Browsers
- Low income  
- More children  
- High web visits  
- Low spending  
➡️ Price-sensitive digital users  

### 🟢 Cluster 1 – High Income Multi-Channel Buyers
- High income  
- High spending  
- Strong store & catalog purchases  
➡️ Loyal premium shoppers  

### 🟡 Cluster 2 – Budget-Conscious Singles
- Low income  
- Live alone  
- High website activity  
➡️ Interested but low purchasing power  

### 🔴 Cluster 3 – High-Value Premium Customers ⭐
- High income  
- Highest spending  
- Best response rate  
➡️ Most profitable segment  

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

## 🚀 Future Improvements

- Deploy using Streamlit dashboard  
- Real-time customer segmentation  
- Recommendation system integration  
- Marketing automation integration  

---

## 👨‍💻 Author

Ishwar Sonawane  
Machine Learning Enthusiast | Python Developer  
