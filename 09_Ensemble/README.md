# Ensemble Learning Algorithms on the Iris Dataset

This project demonstrates and compares several popular **ensemble learning algorithms** using the **Iris dataset**. It explores how different ensemble techniques improve classification performance by combining multiple machine learning models.

## Algorithms Implemented

* Stacking Classifier
* Random Forest (Bagging)
* AdaBoost
* Gradient Boosting
* XGBoost

## Base Models for Stacking

* Decision Tree
* Support Vector Machine (SVM)
* Logistic Regression

**Meta Model**

* Logistic Regression

## Workflow

1. Load the Iris dataset using Seaborn.
2. Prepare features and target labels.
3. Encode class labels using `LabelEncoder`.
4. Split the dataset into training and testing sets.
5. Build and train the following ensemble models:

   * Stacking Classifier
   * Random Forest
   * AdaBoost
   * Gradient Boosting
   * XGBoost
6. Generate predictions on the test set.
7. Evaluate model performance using Accuracy Score.

## Technologies Used

* Python
* Pandas
* NumPy
* Seaborn
* Scikit-learn
* XGBoost

## Learning Objectives

* Understand the differences between Bagging, Boosting, and Stacking.
* Learn how to implement ensemble learning algorithms using Scikit-learn.
* Compare the performance of different ensemble methods on a multiclass classification problem.
* Gain hands-on experience with modern machine learning workflows.

## Dataset

* **Iris Dataset** (loaded using Seaborn)
* **Target Variable:** Species
* **Classification Type:** Multiclass Classification
