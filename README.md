# intrusion_detection_using_ML

###About
This project focuses on building a Network Intrusion Detection System (IDS) using multiple machine learning classifiers. The goal is to classify network traffic and detect potential intrusions. The dataset used contains 13 features for each network connection and a label indicating whether the connection is normal or an intrusion. The project experiments with various classifiers, evaluates their performance, and visualizes the decision boundaries.

###Features
Data Preprocessing:
Encoding categorical features using LabelEncoder.
Splitting the dataset into training and testing sets.
Standardizing the features.
Model Training:
Training multiple classifiers: Logistic Regression, Random Forest, Support Vector Machines (linear, poly, rbf, sigmoid), Decision Tree, Gaussian Naive Bayes, and K-nearest Neighbors.
Applying Principal Component Analysis (PCA) for dimensionality reduction.
Performance Evaluation:
Calculating accuracy, precision, and recall for each model.
Visualizing the decision boundaries for classifiers using 2D plots.
Parallel Processing:
Providing options to run all classifiers serially or in parallel to compare performance.
