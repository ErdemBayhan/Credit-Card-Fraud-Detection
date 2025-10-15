Credit Card Fraud Detection using Machine Learning
A machine learning project focused on detecting fraudulent credit card transactions from a real-world dataset. The core challenge of this project is addressing the significant class imbalance inherent in fraud detection datasets.

This repository contains the code and methodology used to train and evaluate several classification models, with a special focus on the SMOTE (Synthetic Minority Over-sampling Technique) to enhance model performance.

🎯 Project Goal

The main objective is to develop and compare various machine learning models to accurately identify fraudulent credit card transactions. The project highlights the process of handling imbalanced data and evaluates models based on a comprehensive suite of metrics to determine the most effective classifier for this task.

🔧 Technologies & Libraries Used
Python


Scikit-learn: For model implementation (Random Forest, Decision Tree, XGBoost) and evaluation.


imbalanced-learn: For implementing the SMOTE technique.

Pandas: For data manipulation and analysis.

NumPy: For numerical operations.

Matplotlib / Seaborn: For data visualization.

📊 Methodology
The project followed these key steps:


Data Loading and Exploration: The real-world dataset was loaded and analyzed to understand its structure and the extent of the class imbalance.

Data Preprocessing: Data was cleaned and prepared for model training. This included scaling numerical features.


Handling Class Imbalance with SMOTE: The SMOTE (Synthetic Minority Over-sampling Technique) was applied to the training data to generate synthetic samples for the minority class (fraudulent transactions), creating a balanced dataset.

Model Training: Several classification algorithms were trained on the balanced dataset, including:

Decision Tree

Random Forest

XGBoost

Model Evaluation: The models were evaluated on the original, imbalanced test set using a comprehensive suite of metrics suitable for fraud detection, such as Precision, Recall, F1-Score, and AUC-ROC.

📈 Results

After a thorough comparison and evaluation, the Random Forest model demonstrated the best overall performance across the chosen metrics, proving to be the most effective classifier for this fraud detection task.
