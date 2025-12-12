# Breast-Cancer-Knn-Kmeans
Breast Cancer Diagnosis Prediction using KNN and K-Means
This project is about predicting whether a breast cancer case is malignant or benign using machine learning. I used K-Nearest Neighbors (KNN) for supervised classification and K-Means Clustering for unsupervised grouping. The goal was to see how well these algorithms can identify cancer types from the dataset.

## What I did (short)
- Cleaned and preprocessed the dataset (dropped `id`, `Unnamed: 32`, encoded diagnosis).  
- Scaled features using **Min-Max Normalization**.  
- Split data: **80% train / 20% test**.  
- Ran **K-Means (k=2)** to inspect unsupervised grouping.  
- Trained **KNN (k=5)** and evaluated with **accuracy, precision, recall, F1-score**, and a confusion matrix.  
- Included visualizations (PCA for 2D cluster view and confusion matrix heatmap).

---

## Files

Breast-Cancer-KNN-KMeans/
├── dataset/
│ └── breast_cancer.csv # dataset (place here)
├── notebooks/
│ └── Breast_Cancer_Prediction.ipynb # Colab / Jupyter notebook
└── README.md

This project helped me understand how basic preprocessing, clustering, and classification work in machine learning.
KNN gave solid classification results, and K-Means provided insight into how the data naturally groups itself, even without labels.

If I continue this project, I might try:

Hyperparameter tuning (GridSearchCV)

Trying other models like SVM or Random Forest

Adding basic visualizations to better understand clusters
