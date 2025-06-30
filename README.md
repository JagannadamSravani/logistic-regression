Logistic Regression and Breast Cancer Classification Using Machine Learning
🧠 Project Overview
This project focuses on building and evaluating multiple machine learning classification models—including Logistic Regression—to assist in the early detection of breast cancer. The models are trained on a medical dataset, and the objective is to help medical professionals make more accurate diagnoses.

📊 Dataset
The dataset contains features relevant to diagnosing breast cancer.

These features include cell characteristics measured from digitized images of breast tissue samples.

The target variable is binary: benign (0) or malignant (1).

🎯 Objectives
Perform exploratory data analysis and understand feature relationships using correlation heatmaps.

Preprocess the data (e.g., normalization, train-test split).

Build and evaluate multiple classifiers:

Logistic Regression

K-Nearest Neighbors (KNN)

Naive Bayes

Support Vector Machine (SVM)

Decision Tree

Random Forest

Compare model performances using accuracy, precision, recall, F1 score, and confusion matrix.

📈 Logistic Regression Results
Metric	Value
Accuracy	0.9649
Precision	0.9756
Recall	0.9302
F1 Score	0.9524
Confusion Matrix	[[70, 1], [3, 40]]

🔍 Inference
The Logistic Regression model performs well with:

High accuracy and precision, indicating strong general performance.

Good recall and F1 score, meaning the model is effective in correctly identifying malignant cases with minimal false negatives.

A confusion matrix showing only 4 misclassifications out of 114 total samples.

🧪 Model Comparison
All models were compared using consistent metrics. While Decision Tree and Naive Bayes also performed well, Logistic Regression offered a strong balance between interpretability and predictive accuracy.

🩺 Final Conclusion
Machine learning models can significantly aid in the early detection of breast cancer. Logistic Regression, with its simplicity and solid performance, is a strong candidate for clinical use. However, model choice should align with the specific goals:

Minimize false negatives? → Use Naive Bayes

Explain decisions to doctors? → Use Decision Tree

High overall accuracy? → Logistic Regression or Random Forest

