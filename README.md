# Week1-Waterqualityprediction
Overview:
This project focuses on building a predictive model to assess the potability and safety of water based on multiple physicochemical parameters. The primary goal is to automate the process of determining whether water is safe for human consumption, thereby contributing to public health, environmental monitoring, and efficient resource management.

Problem Statement:
Traditional methods for water quality testing are often time-consuming, costly, and require lab equipment. This project proposes a data-driven approach using machine learning models that can predict water quality instantly based on input parameters, enabling quick decision-making for water treatment and management authorities.

Dataset Used:
The dataset consists of multiple chemical properties of water samples, including:

pH level
Hardness
Solids (ppm)
Chloramines
Sulfate
Conductivity
Organic carbon
Trihalomethanes
Turbidity
Potability (target variable: 0 = not safe, 1 = safe)

Methodology:
Data Cleaning & Preprocessing: Handling missing values, normalization, and outlier removal.

Exploratory Data Analysis (EDA): Visualizing the relationship between features and identifying the most influential parameters.

Model Building: Implemented and compared various algorithms like:

Logistic Regression
Decision Tree Classifier
Random Forest
Support Vector Machines (SVM)
K-Nearest Neighbors (KNN)

Evaluation Metrics: Accuracy, F1-score, Confusion Matrix, ROC-AUC curve.

Hyperparameter Tuning: Applied GridSearchCV for optimal model performance.
