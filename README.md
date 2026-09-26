## Obesity Classification Using Machine Learning

📌 Project Overview

This project focuses on predicting obesity levels using Machine Learning classification algorithms based on lifestyle, physical, and behavioral attributes.

The dataset contains information such as age, height, weight, eating habits, physical activity, transportation methods, and family history. The target variable "NObeyesdad" contains 7 obesity-level categories.

🎯 Objective

The main objective of this project is to:

- Perform data preprocessing and feature engineering
- Encode categorical features
- Scale numerical features
- Build and evaluate multiple classification models
- Compare model performance using classification metrics
- Save the preprocessed data and preprocessing objects using Pickle

📊 Dataset

The dataset contains 2,111 records and 17 columns, including the target variable.

Target Variable

"NObeyesdad"

It contains the following classes:

- Insufficient_Weight
- Normal_Weight
- Overweight_Level_I
- Overweight_Level_II
- Obesity_Type_I
- Obesity_Type_II
- Obesity_Type_III

Features

Numerical features:

- Age
- Height
- Weight
- FCVC
- NCP
- CH2O
- FAF
- TUE

Categorical features:

- Gender
- family_history_with_overweight
- FAVC
- CAEC
- SMOKE
- SCC
- CALC
- MTRANS

🔧 Data Preprocessing

The following preprocessing steps were performed:

1. Checked for missing values
2. Checked for duplicate records
3. Separated input features ("X") and target ("y")
4. Encoded the target using "LabelEncoder"
5. Performed train-test split
6. Applied "OneHotEncoder" to categorical features
7. Applied "StandardScaler" to numerical features
8. Used "ColumnTransformer" to combine the preprocessing steps

The encoder and scaler were fitted only on the training data to avoid data leakage.

🤖 Machine Learning Models

The following classification algorithms are implemented:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- Naive Bayes
- Gradient Boosting
- XGBoost

📈 Model Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

Model performances are compared to understand how different classification algorithms perform on the dataset.

💾 Pickle

The preprocessing stage saves the following objects using Pickle:

- "X_train"
- "X_test"
- "y_train"
- "y_test"
- "preprocessor"
- "label_encoder"

The saved Pickle file can be loaded in the classification notebook, allowing the models to be implemented without repeating the preprocessing steps.

📁 Project Structure

Obesity-Classification-ML/
│
├── preprocessing.ipynb
├── classification.ipynb
├── obesity_preprocessed.pkl
├── README.md
├── obesity.csv

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab
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
Categorical Encoding
   ↓
Numerical Scaling
   ↓
Preprocessed Data
   ↓
Classification Models
   ↓
Model Evaluation
   ↓
Model Comparison

👩‍💻 Author

Divya K

B.Tech | Aspiring AI Engineer

⭐ Conclusion

This project demonstrates a complete multi-class classification workflow, from data preprocessing to implementing and evaluating multiple Machine Learning algorithms for obesity-level prediction.
