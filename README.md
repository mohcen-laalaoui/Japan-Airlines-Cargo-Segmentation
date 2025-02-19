# Japan Airlines Cargo Segmentation

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## ✈️ Overview
This project segments **Japan Airlines cargo traffic** based on **weight** and **volume** using **K-Means clustering**. The goal is to group cargo shipments into meaningful clusters, helping to optimize logistics and identify cargo patterns.

---

## 📊 Dataset
The dataset contains the following key features:

- **Weight_kg**: Weight of the cargo in kilograms.
- **Volume_m3**: Volume of the cargo in cubic meters.
- Additional columns such as `Cargo_ID`, `Date`, `Origin`, and `Destination` are retained for analysis.

---

## 🔥 Features
- ✅ **Custom K-Means Implementation**: Built from scratch in PyTorch, allowing full control over clustering.
- 🔄 **Data Preprocessing**: Includes feature selection, scaling, and handling missing values.
- 📈 **Cluster Analysis**: Computes key statistics like mean weight and volume for each cluster.
- 🎨 **Visualization**: Generates scatter plots with centroids for better interpretation.
- 💾 **Export Results**: Saves segmented data to CSV for further analysis.

---

## 🛠 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/mohcen-laalaoui/Japan-Airlines-Cargo-Segmentation.git
   cd Japan-Airlines-Cargo-Segmentation
## 🧪 Methodology
### 1️⃣ Data Preprocessing
- 🔍 Handling missing values
- ⚖️ Feature scaling to normalize weight and volume
- 🎯 Feature selection to focus on relevant data
### 2️⃣ K-Means Clustering
- 🏆 Optimal Cluster Selection: Uses techniques like the Elbow Method
- 🔢 Model Parameters: Iterates over centroids to minimize inertia
- 📊 Validation Metrics: Evaluates clustering effectiveness
## 📊 Results
- 🚛 Cluster Descriptions: Each cluster represents a unique segment of cargo traffic
- 🔑 Key Insights: Patterns observed in the weight-volume distribution
- 📉 Visualization: Plots clusters along with their centroids for better understanding
## 🚀 Future Improvements
- Implement Hierarchical Clustering for comparison
- Experiment with different distance metrics for better segmentation
- Automate hyperparameter tuning for K-Means
# 👨‍💻 Author
## 📌 Mohcen Laalaoui
### 💼 Machine Learning & Data Science Enthusiast
