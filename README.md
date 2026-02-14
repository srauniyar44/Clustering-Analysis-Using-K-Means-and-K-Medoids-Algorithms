# MSCS 634 - Lab 3
## K-Means and K-Medoids Clustering on Wine Dataset

### Purpose
This lab implements and compares K-Means and K-Medoids clustering on the Wine dataset using standardized features.

### Key Insights
- K-Means generally produces compact spherical clusters.
- K-Medoids is more robust to outliers since medoids are actual data points.
- Silhouette Score evaluates cluster separation.
- Adjusted Rand Index compares clustering to true labels.

### Observations
Standardization significantly improved clustering performance.
K-Means was computationally faster.
K-Medoids may be preferable when robustness is required.

### Requirements
Install required packages:
pip install scikit-learn scikit-learn-extra matplotlib pandas numpy
