
# Unsupervised Tumor Classification: Clustering and Dimensionality Reduction

This project explores the use of unsupervised learning techniques, particularly **K-Means clustering**, to classify tumors into benign and malignant categories. The analysis focuses on dimensionality reduction methods, such as **PCA** and **t-SNE**, to visualize and improve the clustering process.

## Overview

Medical datasets often lack labeled data, making unsupervised learning a valuable tool for exploratory analysis and preliminary classification tasks. This project demonstrates how clustering can achieve high accuracy in distinguishing between tumor types, even without labeled training data.

## Key Features

- **Clustering with K-Means**:
  - Optimal number of clusters determined using the Elbow Method and Silhouette Analysis.
  - High accuracy (90.6%) achieved in classifying tumors.

- **Dimensionality Reduction**:
  - **PCA** (Principal Component Analysis) to visualize clusters in 2D.
  - **t-SNE** for enhanced cluster separation and visualization.

- **Confusion Matrix**:
  - Comparison of clustering results with the original diagnosis labels for accuracy evaluation.

## Dataset

The dataset used contains tumor-related features such as:
- Tumor radius, texture, perimeter, and other measurable properties.
- Diagnosis labels: `B` (Benign) and `M` (Malignant).


## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/unsupervised-tumor-classification.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook tumor_classification.ipynb
   ```

## Results

- **Confusion Matrix**:
  - High classification accuracy for both PCA and t-SNE approaches.
  - Majority of tumors were correctly classified into benign or malignant clusters.

- **Cluster Visualization**:
  - PCA and t-SNE enabled visualization of cluster separations in 2D space.
  - t-SNE provided a more distinctive separation between clusters.

## Future Improvements

- Explore additional dimensionality reduction methods.
- Test alternative clustering algorithms like **DBSCAN** or **Hierarchical Clustering**.
- Evaluate performance with datasets containing higher dimensionality or more complexity.

## Author

- **Patricio Moore**
- [GitHub Profile](https://github.com/patymoore)
- [LinkedIn Profile](https://www.linkedin.com/in/patricio-moore-bb3b2b121/)


