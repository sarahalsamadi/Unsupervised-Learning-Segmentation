# 📊 Unsupervised Learning Segmentation

This repository contains a specialized project focused on **Unsupervised Learning** to segment data points into distinct performance categories. By utilizing clustering algorithms, the project identifies hidden patterns and classifies observations into meaningful groups such as "Excellent," "Good," and "Weak" performance based on ROI metrics.

## 🚀 Overview
The core objective is to group data without prior labels, then apply a logical mapping to evaluate the quality of each cluster. This approach is highly effective for student performance analysis, customer segmentation, or financial ROI tracking.

## 🛠️ Tech Stack
- **Language:** Python 🐍
- **Key Libraries:**
  - `Scikit-learn`: For KMeans clustering and data scaling.
  - `Scipy`: For Hierarchical clustering and Dendrogram visualization.
  - `Pandas` & `NumPy`: For data manipulation and ROI calculations.
  - `Matplotlib` & `Seaborn`: For generating insightful statistical plots.

## 📊 Project Workflow
1. **Data Normalization:** Using `StandardScaler` to ensure all features contribute equally to the distance metrics.
2. **KMeans Clustering:** Implementation of the **Elbow Method** and **Silhouette Analysis** to determine the optimal number of clusters.
3. **Hierarchical Analysis:** Building a **Dendrogram** to understand the nested relationships within the data.
4. **Automated Labeling:** A custom logic that ranks clusters based on their mean ROI and assigns performance tiers (Excellent 🟢, Good 🔵, Weak 🟠).

## ⚙️ Installation & Usage
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/sarahalsamadi/
Unsupervised-Learning-Segmentation.git](https://github.com/sarahalsamadi/
Unsupervised-Learning-Segmentation.git)

2. **Install required dependencies:**
   ```bash
   pip install -r Requirements.txt
  
3. **Run the analysis:**
    Open clustring.ipynb in Jupyter Notebook or VS Code and execute the cells to see the clustering results.


## 📝 Key Features
. **Smart Labeling:** Automatically identifies which cluster represents the highest performance.
. **Visual Insights:** High-quality visualizations including cluster scatter plots and hierarchy trees.
. **Evaluation Metrics:** Uses Silhouette scores to validate the mathematical consistency of the clusters.  
