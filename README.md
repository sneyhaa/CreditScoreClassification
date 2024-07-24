## Credit Score Prediction with Machine Learning

The goal of this project is to build a predictive model to classify credit scores into three categories: Good, Standard, and Poor. The project explores various machine learning models to identify the most effective one for credit score prediction.

**Motivation:**

Many individuals struggle with managing their finances, and credit scores, while valuable for assessing financial health, lack predictive power. This project aims to bridge that gap.

**Objective:**

* Evaluate and compare the performance of various machine learning models for credit score classification.
* Identify the most accurate model for predicting credit scores.
  
**Methodology:**

1. **Data Preprocessing:**
   * Cleaned data by removing errors, outliers, and handling missing values.
   * Encoded categorical features for machine learning compatibility.
   * Applied feature selection and dimensionality reduction techniques to optimize training. 
   * Addressed class imbalance, if present, to ensure balanced representation of credit score categories.

2. **Models and Evaluation:**
The following models were tested and evaluated:
* Logistic Regression
* Gradient Boosting
* Support Vector Machine (SVM)
* Decision Tree
* Random Forest
* Voting Classifier (Ensemble of Decision Tree, Random Forest, and Gradient Boosting)

**Metrics Used:**
* Accuracy: Overall correctness of the model.
* Precision: Proportion of positive identifications that were actually correct.
* Recall: Proportion of actual positives that were identified correctly.
* F1-Score: Weighted average of precision and recall.

**Results**
The ensemble model (Voting Classifier) achieved the highest performance with an accuracy of 72.26% and balanced precision, recall, and F1-scores across all classes. The confusion matrix and classification report for each model are included in the results.
