**Supervised Learning Projects**
This repository contains hands-on rojects focused on supervised learning techniques using Python and scikit-learn.
Each project demonstrates a different algorithem or application, complete with model training, evaluation, and visualization

**1. K-Nearest Neighbors Classification - Handwritten Digits**
   Location: supervised_algorithm/knn_digits.ipynb
   Goal: Use KNN to classify images of handwritten digits from the scikit digits dataset.
   Key Features:
   - Loads digit images using load_digits()
   - Splits data into training and test sets
   - Trains a KNN classifier using KNeighborsClassifier
   - Evaluate with:
       - Accuracy
       - Confusion matrix
   - Performs PCA (2D) to reduce dimensionality for visualization
  
**2. K-Nearest Neighbors Regression - California Housing**
   Location: supervised_algorithm/knn_regression/knn_regression.ipynb
   Goal: Predict median house values using KNN regression on the California Housing dataset.
   Key Features:
   - Loads data using fetch_california_housing()
   - Split data into training and testing sets
   - Trains a KNN Regressor using KNeighborsRegressor
   - Evaluate with:
       - Mean Squared Error (MSE)
       - R2 Score

