# 🩺 HealthClusters: Unveiling Hidden Patient Groups Through Unsupervised Learning

## 📖 Overview
This project applies unsupervised machine learning to cluster patients based on clinical, demographic, and lifestyle data. The goal is to discover hidden patterns for risk profiling, early intervention, and targeted care.

---

## 📊 Dataset
The dataset includes attributes such as:

- 👥 **Demographics:** age, gender, residence type, smoking status  
- 🧪 **Clinical Metrics:** blood pressure, cholesterol, glucose, BMI  
- ❤️ **Medical History:** heart disease, hypertension  
- 🏃 **Lifestyle:** physical activity, smoking  

---

## ⚙️ Preprocessing
- **Encoding:** Categorical features (e.g., smoking status) encoded with `LabelEncoder`  
- **Scaling:** Used `MinMaxScaler`, `StandardScaler`, and `RobustScaler`  
- **Feature Engineering:** PCA for dimensionality reduction, polynomial features for non-linearity, and `SelectKBest` for feature selection  

---

## 🤖 Clustering Techniques
- **K-Means** – Fast, good for spherical clusters  
- **DBSCAN** – Density-based, detects outliers  
- **GMM** – Probabilistic soft clustering  
- **Agglomerative** – Hierarchical, reveals multi-level structure  

---

## 🏆 Outcome
The resulting clusters offer insights into patient risk groups and support healthcare decision-making with interpretable patterns.
