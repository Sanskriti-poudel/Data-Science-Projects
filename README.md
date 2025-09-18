In this project, we built a Linear Regression model using the Boston Housing dataset to predict house prices.

Steps we followed:

Loaded the dataset (Boston Housing from sklearn.datasets).

Prepared the data by separating features (X) and target (y), dropping unnecessary columns.

Split the data into training and testing sets using train_test_split.

Trained a Linear Regression model with scikit-learn.

Saved the trained model and feature names using joblib.

Created a prediction script that:

Loads the saved model

Accepts user input for all features

Predicts the house price based on input values

This workflow demonstrates the complete process of training, saving, and using a machine learning model for predictions.
