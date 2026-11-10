# Machine Learning Midterm Project

**Author:** Mehmet Akif Çetinkaya  
**Student ID:** 23040202006  

This repository contains the code, output files, and the final report for the Machine Learning Midterm Assignment. 

## Project Overview
The project evaluates supervised and unsupervised machine learning algorithms on two datasets:
1. **Breast Cancer Wisconsin Dataset** (Binary Classification)
2. **Wine Classification Dataset** (Multi-class Classification)

## Methodology
- **Preprocessing:** A strict hold-out test set (20%) was reserved. The remaining data was repeatedly split into training and validation subsets using seeds (42, 52, 62). `StandardScaler` was applied exclusively to the training subsets to prevent data leakage.
- **Classification:** Decision Tree, K-Nearest Neighbors (KNN), and Gaussian Naive Bayes. KNN (k=7) performed best on the scaled representation for both datasets.
- **Clustering:** K-Means clustering (n_clusters = 2 for Breast Cancer, 3 for Wine) was evaluated using the Adjusted Rand Index (ARI).

## Repository Contents
- `breast_cancer.ipynb` & `wine.ipynb`: Jupyter notebooks containing the full machine learning pipelines.
- `report.docx`: Final comprehensive report with evaluation metrics, figures, and interpretations.
- `*.csv`: Output files for classifier validation, final test scores, and K-Means summaries.
- `AI_DISCLOSURE.md`: Declaration of AI tools used during the project.
