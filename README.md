# task-7-Use-SVMs-for-linear-and-non-linear-classification
AI &  ML Internship - task 7Use SVMs for linear and non-linear classification








. Objective




To implement Support Vector Machine (SVM) for binary classification using linear and RBF kernels.



. Tools & Libraries Used

Python

Scikit-learn

NumPy

Matplotlib

Google Colab



. Dataset Used



Breast Cancer Wisconsin Dataset

Binary Classification Problem (Malignant / Benign)

. Steps Performed



1️ Data Loading



Loaded dataset using sklearn datasets module.

2️  Data Splitting


Split dataset into training and testing sets using train_test_split().

3️ Feature Scaling



Applied StandardScaler because SVM is sensitive to feature scale.

4️ Model Training



Trained SVM with Linear Kernel

Trained SVM with RBF Kernel

5️  Hyperparameter Tuning



Tuned:

C parameter

Gamma parameter (for RBF)

6️  Model Evaluation



Accuracy Score

Cross Validation

Classification Report

7️  Decision Boundary Visualization



Plotted 2D decision boundary using Matplotlib.

. Results


Kernel	Accuracy
Linear	~95%
RBF	~97%

RBF kernel performed slightly better.

. Concepts Learned




Margin Maximization

Kernel Trick

Overfitting Control using C

Cross Validation
In this task, Support Vector Machine (SVM) was successfully implemented for binary classification using both Linear and RBF kernels. The model was trained and evaluated on the Breast Cancer Wisconsin Dataset using tools from Scikit-learn.
