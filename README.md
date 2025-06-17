# SCT_DS_TASK.NO3
🧠 Bank Marketing Prediction using Decision Tree Classifier
📌 Project Overview
This project builds a Decision Tree Classifier to predict whether a customer will subscribe to a term deposit, based on their demographic and behavioral attributes. The model is trained using the Bank Marketing Dataset from the UCI Machine Learning Repository.

📁 Dataset Information
Dataset: bank-additional-full.csv

Source: UCI Machine Learning Repository

Size: 41,188 records, 21 features

Target Variable: y — indicates if the client subscribed to a term deposit (yes or no)

✅ Objective
To build a machine learning model using a Decision Tree Classifier that can:

Accurately predict if a customer will purchase a product (term deposit).

Analyze and visualize feature importance.

Evaluate the model using classification metrics.

🛠️ Tools & Libraries
Python

pandas, NumPy

scikit-learn

matplotlib

seaborn (optional for visualization)

🔄 Workflow
Data Preprocessing

Label Encoding for categorical features

Train-Test Split (70-30)

Model Building

Decision Tree Classifier from sklearn

Evaluation

Accuracy: ~88%

Classification Report

Confusion Matrix

Feature Importance Plot

📊 Results
Model Accuracy: 88%

Key Observations:

Most important features: duration, contact, month, age

The model tends to predict well for the majority class (no) but may need tuning or balancing for better yes predictions.

📷 Visuals
Include screenshots or generated plots like:

Decision Tree plot

Feature importance bar chart

Confusion matrix
