# Titanic - Machine Learning from Disaster

This project is a submission to a Kaggle competition aimed at predicting the number of people who survived the Titanic disaster. The dataset provided by Kaggle contains various features about the passengers on board and the objective is to develop an accurate predictive model using support vector machines (SVMs).

Three different types of support vector machines (SVMs) have been implemented and evaluated to assess their accuracy and suitability for the given dataset: LinearSVC, SVC and NuSVC.

The performance of each SVM variant was assessed using cross-validation and evaluation metrics such as accuracy and F1-score. The results are summarized and compared to determine the most effective SVM model for the dataset.

Based on the experimental results, the Nu-SVC model with hypertuned parameters (nu=0.3, kernel='poly', gamma=1) outperformed other variants with an accuracy of 81.34% and an F1-score of 0.73. Further optimizations and model tuning may be explored to enhance predictive performance.
