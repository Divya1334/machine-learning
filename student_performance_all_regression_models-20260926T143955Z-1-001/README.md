## Student Performance Regression

📌 Project Overview

This project focuses on predicting student performance using Machine Learning regression algorithms.

The project follows a complete Machine Learning workflow, including data preprocessing, feature transformation, model training, prediction, and evaluation.

🎯 Objective

The main objective is to predict a student's performance score based on relevant academic, demographic, and other available features in the dataset.

🔧 Data Preprocessing

The following preprocessing steps were performed:

- Checked for missing values
- Checked for duplicate records
- Separated input features ("X") and target ("y")
- Identified numerical and categorical features
- Applied One-Hot Encoding to categorical features
- Applied Standard Scaling to numerical features
- Performed Train-Test Split
- Used "ColumnTransformer" for preprocessing
- Saved the preprocessed data and preprocessing object using Pickle

🤖 Regression Models

The following Machine Learning regression algorithms were implemented:

- Linear Regression
- K-Nearest Neighbors (KNN) Regression
- Decision Tree Regression
- Random Forest Regression
- Gradient Boosting Regression
- Support Vector Regression (SVR)
- XGBoost Regression

📊 Model Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

📈 Model Comparison

The performance of all regression models was compared using the above evaluation metrics to understand their performance on the student performance dataset.

💾 Pickle

The preprocessing stage saves the processed training and testing data along with the preprocessing object using Pickle.

This allows the regression models to be implemented in a separate notebook without repeating the preprocessing steps.

📁 Project Structure

Student_Regression/
│
├── preprocessing.ipynb
├── regression.ipynb
├── regression_preprocessed.pkl
├── README.md
└── student_performance.csv

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook
- Google Colab
- Pickle

🚀 Project Workflow

Dataset
   ↓
Data Cleaning
   ↓
Feature & Target Separation
   ↓
Train-Test Split
   ↓
Encoding & Scaling
   ↓
Pickle
   ↓
Load Preprocessed Data
   ↓
Regression Models
   ↓
Prediction
   ↓
Model Evaluation
   ↓
Model Comparison

👩‍💻 Author

Divya K

B.Tech | Aspiring AI Engineer

⭐ Conclusion

This project demonstrates an end-to-end Machine Learning regression workflow for predicting student performance and provides practical implementation of multiple regression algorithms.
