Project Title Customer Churn Prediction using Machine Learning and Deep Learning Integration

Problem Statement Customer churn is a major challenge faced by companies, especially in the telecom sector. Retaining existing customers is more cost-effective than acquiring new ones. However, identifying customers who are likely to churn is difficult. This project aims to build a predictive model using Machine Learning and Deep Learning techniques to identify at-risk customers early and help businesses take preventive actions.

Pipeline Diagram Data Collection → Data Preprocessing → Feature Engineering → Train-Test Split → ML Model Training (5 Models) → Evaluation → Ensemble Learning → Deep Learning (ANN) → ML + DL Integration → Final Comparison & Visualization Dataset Details Source: Synthetic dataset (self-generated)

Rows: 4000

Columns: 20

Features: 19 input features

Target Variable: Churn (0 = No, 1 = Yes)

Type: Tabular dataset

Data Preprocessing Missing values handled using mean imputation

Feature scaling using StandardScaler

Removed irrelevant columns (CustomerID)

Feature Engineering Created new feature: AvgChargePerService = MonthlyCharges / (Services + 1)

Models Used Machine Learning Models Logistic Regression

Decision Tree

Random Forest

K-Nearest Neighbors (KNN)

Naive Bayes

Ensemble Learning Voting Classifier

Deep Learning Model Artificial Neural Network (ANN)

Dense layers

ReLU activation

Sigmoid output layer

Dropout for overfitting prevention

Model Training Train-Test Split (80:20)

5-Fold Cross Validation used for multiple training

Evaluation Metrics Accuracy

Precision

Recall

F1 Score

ML + DL Integration ANN predictions used as additional feature

Best ML model retrained with enhanced dataset

Improved overall performance

Results & Comparison Model Accuracy Precision Recall F1 Score Logistic Regression XX XX XX XX Decision Tree XX XX XX XX Random Forest XX XX XX XX KNN XX XX XX XX Naive Bayes XX XX XX XX Ensemble XX XX XX XX ANN XX XX XX XX Integrated Model XX XX XX XX Visualization Bar charts for model comparison

Confusion matrix for classification

Insights & Observations Random Forest performed best among ML models

Ensemble learning improved model stability

ANN captured complex non-linear patterns

Integrated model improved overall prediction performance

Overfitting / Underfitting Cross-validation used to reduce overfitting

Dropout applied in ANN

Balanced performance between training and testing

Technologies Used Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

TensorFlow / Keras

Steps to Run the Project Clone repository

git clone Install dependencies

pip install pandas numpy matplotlib scikit-learn tensorflow seaborn Run notebook

jupyter notebook Execute all cells

Project Structure ├── churn_prediction.ipynb ├── telecom_churn_dataset.csv ├── README.md Sample Output (Add screenshots here in GitHub)

Team Members Gayathridevi S Nidharshana A Harshidha Devi M Divyabala B

Conclusion This project successfully predicts customer churn using multiple machine learning models and a deep learning approach. The integration of ML and ANN improves prediction accuracy and provides a reliable solution for real-world business applications.
