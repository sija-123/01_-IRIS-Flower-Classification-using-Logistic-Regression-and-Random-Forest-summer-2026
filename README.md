# 01_IRIS_Flower_Classification_using_Logistic_Regression_and_Random_Forest_Summer_2026
Project Report: IRIS Flower Classification
Introduction
This project aimed to classify IRIS flower species using Logistic Regression and Random Forest algorithms. The IRIS dataset, a classic in machine learning, consists of measurements for three different species of Iris flowers: Setosa, Versicolor, and Virginica.

Data Loading and Preparation
The load_iris function from sklearn.datasets was used to load the dataset. The data was then converted into a Pandas DataFrame with appropriate feature names. A 'target' column was added, containing the species labels (0, 1, 2), and its distribution was confirmed to be balanced (50 samples per class).

Feature and Target Separation
The dataset was divided into features (X) and the target variable (y). The X matrix contained the four sepal and petal measurements, while y contained the species labels.

Data Splitting
The data was split into training and testing sets using train_test_split with a test_size of 0.2 and random_state of 42 to ensure reproducibility. This resulted in 120 samples for training and 30 for testing.

Model Training and Evaluation
1. Logistic Regression
A Logistic Regression model was initialized and trained on the X_train and y_train datasets. The model's performance was evaluated on the X_test set, achieving an accuracy of 1.0, indicating perfect classification on the test data.

2. Random Forest
Following Logistic Regression, a Random Forest Classifier was trained. This model was configured with n_estimators=100 and random_state=42. The Random Forest model's performance was also evaluated on the X_test set, and a detailed classification report was generated. Similar to Logistic Regression, the Random Forest model also demonstrated high accuracy on this dataset.

Conclusion
Both Logistic Regression and Random Forest models performed exceptionally well on the IRIS dataset, achieving perfect or near-perfect classification accuracy. This project successfully demonstrated the application of these fundamental machine learning algorithms for multi-class classification tasks.


