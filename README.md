# Employee_Salary_Prediction
This project predicts whether an individual's income is above or below $50K using the UCI Adult Census dataset. It includes data preprocessing, feature encoding, model training with Random Forest, and a Gradio-based web app for live user predictions.

**#Problem Statement**
Build a predictive system that estimates whether an individual’s income exceeds $50K per year based on demographic and employment features. This helps HR, government, and financial sectors to identify high-income individuals using machine learning.

**#System Approach**
Data Collection: Used the UCI Adult Income Dataset.
Data Preprocessing:Removed null/missing values. Label encoded categorical variables (e.g., education, marital status). Scaled numerical features (e.g., age, hours/week).
Feature Engineering: Selected relevant features influencing salary prediction.Handled class imbalance if any.
Model Training:Trained a machine learning model using Random Forest Classifier.
Evaluation: Used accuracy, precision, recall, F1-score to validate performance.
Deployment: Deployed using Gradio to provide a user-friendly interface.

**#Algorithm & Deployment**
Algorithm: Random Forest Classifier
  Random Forest is an ensemble method using multiple decision trees. It improves accuracy and avoids overfitting. Handles both categorical and numerical features well. Ideal for classification tasks like income prediction.
Deployment:Built an interactive Gradio app for real-time predictions.
  User inputs demographic info like age, education, workclass, etc.Model predicts whether income is >50K or <=50K. App hosted locally or shared via public Gradio links.

**#Results**
Accuracy Score: 84.67%
Classification Report:Precision, Recall, F1-score used to measure class-wise performance.
Confusion Matrix: Shows true positives, true negatives, etc.
ROC-AUC Score: Measures model’s ability to distinguish classes.


**#Conclusion**
  A machine learning-based salary prediction system was successfully built and deployed. The model can be integrated with HR tools or government systems. Provides fast and reliable insights based on demographic and professional data.
