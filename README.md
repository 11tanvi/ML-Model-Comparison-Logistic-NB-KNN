Heart Disease Prediction – Model Comparison
Overview

This project compares three machine learning algorithms — Logistic Regression, Gaussian Naive Bayes, and K-Nearest Neighbors (KNN) — on the Kaggle Heart Disease dataset to predict the presence of heart disease.
The goal is to evaluate and compare model performance using standard classification metrics.

Models Used
Logistic Regression
Gaussian Naive Bayes
K-Nearest Neighbors (KNN)

Hyperparameter tuning was performed using GridSearchCV with 5-fold Cross-Validation.

📈 Evaluation Metrics

Models were evaluated using:

Accuracy
Precision
Recall

🏆 Final Results (After Tuning)
Model	                    Accuracy	Recall	Precision
Logistic Regression	        0.852	  0.844	   0.871
Gaussian Naive Bayes	      0.869   0.844	   0.900
KNN	                        0.902	  0.875	   0.933

KNN achieved the highest overall performance on this dataset.

Tools & Libraries
Python
NumPy
Pandas
Matplotlib
Scikit-learn

Key Learnings
Importance of baseline vs tuned models
Effect of hyperparameter tuning
Comparing multiple algorithms before selecting a final model
Model evaluation using Precision and Recall (not just Accuracy)
