# Machine Learning Classification and Clustering Analysis

## Overview
This project explores both supervised and unsupervised machine learning techniques on a structured dataset. The workflow includes preprocessing, class balancing, feature scaling, classification, clustering, dimensionality reduction, and model evaluation. The project compares how different algorithms perform in predicting class labels and identifying hidden patterns in the data.

## Objectives
- Preprocess training and test datasets
- Handle class imbalance using SMOTE
- Apply supervised learning models for classification
- Apply unsupervised learning models for clustering
- Reduce dimensionality using PCA for visualization
- Evaluate model performance using classification and clustering metrics

## Techniques Used
### Supervised Learning
- Decision Tree Classifier
- Support Vector Machine (SVM)

### Unsupervised Learning
- KMeans Clustering
- Gaussian Mixture Model (GMM)

### Preprocessing and Evaluation
- Label Encoding
- StandardScaler
- SMOTE
- PCA
- Accuracy, Precision, Recall, F1 Score
- Confusion Matrix
- Silhouette Score
- Adjusted Rand Index

## Workflow
1. Load training and test datasets
2. Perform exploratory checks on shape, columns, and class distribution
3. Encode target labels
4. Split features and target variables
5. Scale input features
6. Balance the training data using SMOTE
7. Train supervised models:
   - Decision Tree
   - SVM
8. Evaluate classification models using accuracy, F1 score, confusion matrix, and classification report
9. Apply PCA to reduce features to 2 components
10. Perform clustering using:
    - KMeans
    - Gaussian Mixture Model
11. Evaluate clustering quality using silhouette score and adjusted rand index
12. Visualize clustering outputs

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- imbalanced-learn
