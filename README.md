# Japan Airlines Cargo Segmentation

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## Overview
This project segments Japan Airlines cargo traffic based on **weight** and **volume** using the **K-Means clustering algorithm**. The goal is to group cargo shipments into meaningful clusters to better understand patterns and optimize logistics operations.

---

## Dataset
The dataset contains the following columns:
- **Weight_kg**: Weight of the cargo in kilograms.
- **Volume_m3**: Volume of the cargo in cubic meters.
- Other columns (e.g., `Cargo_ID`, `Date`, `Origin`, `Destination`, etc.) are retained for analysis.

---

## Features
- **Custom K-Means Implementation**: The K-Means algorithm is implemented from scratch, providing full control over the clustering process.
- **Data Preprocessing**: The dataset is preprocessed by extracting relevant features and normalizing them.
- **Cluster Analysis**: Mean weight and volume for each cluster are computed and visualized.
- **Visualization**: A scatter plot of the clusters with centroids is generated for better interpretation.
- **Save Results**: The segmented data is saved to a new CSV file for further analysis.

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/mohcen-laalaoui/Japan-Airlines-Cargo-Segmentation.git
   cd Japan-Airlines-Cargo-Segmentation
   pip install numpy pandas scikit-learn matplotlib


# Data Format
## Input Data (japan_airlines_cargo_traffic.csv)

.Column descriptions
.Data types
.Sample format

## Output Data (japan_airlines_cargo_traffic_segmented.csv)

.Segmentation results
.Cluster assignments
.Additional metrics

## Methodology

  ### 1 Data Preprocessing
  .Handling missing values
  .Feature scaling
  .Feature selection

### 2 K-means Clustering
   .Optimal cluster selection
   .Model parameters
   .Validation metrics

## Results
 .Description of identified segments
 .Key insights
 .Visualization explanation               
