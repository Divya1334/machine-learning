# 📱 Cellphone Price Range Prediction using Machine Learning

## 📌 Project Overview
Cellphone Price Range Prediction is a Machine Learning classification project that predicts the price category of a mobile phone based on its technical specifications.

The model analyzes features such as RAM, battery power, internal memory, processor cores, screen dimensions, and camera specifications to classify a mobile phone into one of four price ranges.

## 🎯 Problem Statement
To develop a Machine Learning model that predicts the price range of a mobile phone based on its specifications.

## 🎯 Objectives
- Understand and analyze mobile phone specifications.
- Perform Exploratory Data Analysis (EDA).
- Handle data preprocessing and feature scaling.
- Train and evaluate multiple Machine Learning classification algorithms.
- Perform hyperparameter tuning to improve model performance.
- Select the best-performing model for prediction.

## 📂 Dataset Information
- **Total Records:** 2,000
- **Total Columns:** 21
- **Input Features:** 20
- **Target Variable:** `price_range`

### Target Classes

| Value | Price Category |
|---|---|
| 0 | Low |
| 1 | Medium |
| 2 | High |
| 3 | Very High |

### Important Features
- Battery Power
- RAM
- Internal Memory
- Mobile Weight
- Processor Cores
- Front Camera
- Primary Camera
- Pixel Height and Width
- Screen Height and Width
- 3G, 4G, Wi-Fi and Bluetooth availability

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook / Google Colab

## 🔍 Project Workflow
1. Import required libraries.
2. Load the dataset.
3. Perform data understanding and inspection.
4. Check missing values and duplicate records.
5. Perform Exploratory Data Analysis (EDA).
6. Analyze feature distributions and outliers.
7. Perform feature-target separation.
8. Split the dataset into training and testing sets.
9. Apply feature scaling where required.
10. Train multiple Machine Learning models.
11. Evaluate model performance.
12. Perform hyperparameter tuning.
13. Save the trained model.

## 🤖 Machine Learning Algorithms Used
1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree Classifier
4. Random Forest Classifier
5. Support Vector Machine (SVM)
6. Gaussian Naive Bayes
7. XGBoost Classifier

## 📊 Model Comparison

| S.No | Model | Accuracy (%) |
|---|---|---:|
| 1 | Logistic Regression | 96.50 |
| 2 | KNN | 50.00 |
| 3 | Decision Tree | 83.00 |
| 4 | Random Forest | 88.00 |
| 5 | SVM | 89.50 |
| 6 | Gaussian Naive Bayes | 81.00 |
| 7 | XGBoost | 91.25 |

## ⚙️ Hyperparameter Tuning
Logistic Regression was selected for hyperparameter tuning because it achieved the highest initial accuracy.

GridSearchCV was used with 5-fold cross-validation.

Best parameters from the earlier experiment:
- **C:** 100
- **Solver:** lbfgs
- **Maximum Iterations:** 1000

**Earlier experiment test accuracy:** 98.25%

## 🏆 Final Model
Logistic Regression was selected as the best-performing model based on the initial model comparison and the earlier hyperparameter tuning experiment.

## 💾 Model Saving
The trained model was saved using Pickle for future use and predictions.

## 🚀 Applications
- Mobile phone price category estimation.
- Mobile specification analysis.
- Supporting price-range decisions for mobile sellers and buyers.

## 🔮 Future Enhancements
- Develop a web application using Flask or Streamlit.
- Build a user-friendly interface for entering mobile specifications.
- Deploy the trained model for real-time predictions.

## 👩‍💻 Author
**Divya K**

