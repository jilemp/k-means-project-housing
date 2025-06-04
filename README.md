
# 🗺️ K-Means Clustering on California Housing Data

This project demonstrates how to apply **unsupervised machine learning** using the **K-Means clustering algorithm** on real-world housing data. The goal is to explore regional patterns based on geographical and economic features.

## 🔍 Overview

Using a simplified dataset from California housing data, we:

- Load and preprocess data with **pandas**
- Apply **K-Means clustering** to group similar housing regions
- Visualize clusters on a map using **Plotly**
- (Optional) Explore **RandomForestClassifier** for classification tasks

## 📁 Dataset

The dataset is publicly available and loaded directly from:

```
https://raw.githubusercontent.com/4GeeksAcademy/k-means-project-tutorial/main/housing.csv
```

Only the following features are used for clustering:
- `Latitude`
- `Longitude`
- `MedInc` (Median Income)

## ⚙️ Technologies Used

- `pandas`, `numpy` – Data manipulation
- `scikit-learn` – Clustering & machine learning models
- `plotly.express` – Interactive data visualization
- `Jupyter Notebook` – Exploratory data analysis and workflow

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/jilemp/k-means-project-housing.git
   ```
2. Navigate to the project folder:
   ```bash
   cd your-repo-name
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "explore.ipynb"
   ```
4. Run each cell in sequence.

## 📊 Results

- The K-Means algorithm segments California into **6 distinct clusters** based on income and geography.
- Interactive plots show how clusters are distributed spatially.

## 🧠 Future Work

- Evaluate clustering performance using metrics like Silhouette Score
- Add classification using `RandomForestClassifier`
- Enhance feature selection (e.g., include population, house age)

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

> Made using Jupyter & scikit-learn
