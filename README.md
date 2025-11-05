---Iris Flower Classification using Scikit-learn
-- Overview

This project demonstrates an end-to-end machine learning workflow using the Iris dataset. The goal is to predict the species of iris flowers (Setosa, Versicolor, Virginica) based on four key features: sepal length, sepal width, petal length, and petal width.

Built using Python and Scikit-learn, this project covers all essential ML stages — data preprocessing, model training, evaluation, and saving the trained model for reuse. It’s ideal for beginners learning supervised learning and Scikit-learn workflows.

--Tech Stack

-Language: Python

-Libraries: scikit-learn, pandas, numpy, matplotlib, seaborn, joblib

-IDE: Jupyter Notebook / VS Code

--Workflow

-Load Dataset – Imported Iris dataset from sklearn.datasets.

-Preprocess Data – Scaled features using StandardScaler.

-Train Models – Trained Logistic Regression, KNN, Decision Tree, and SVM.

-Evaluate Performance – Used accuracy, confusion matrix, and classification report.

-Build Pipeline – Combined scaling and model training into a clean pipeline.

-Save Model – Serialized best model using joblib for later use.

---Results
Model	Accuracy
Logistic Regression	100%
Decision Tree	100%
SVM	100%
KNN	96.6%

Confusion Matrix: Perfect diagonal — zero misclassifications.

--Future Enhancements

-Add hyperparameter tuning with GridSearchCV.

-Deploy model using Flask or Streamlit.

-Extend to larger or noisy datasets.

--Keywords: Machine Learning, Scikit-learn, Classification, Iris Dataset, Python
