# Blood Donation Prediction Using Machine Learning

## Project Overview
This project predicts whether an individual is likely to donate blood in March 2007 based on their previous blood donation history. It uses supervised Machine Learning classification algorithms to analyze donor behaviour.

## Dataset
- Total records: 576
- Target: Made Donation in March 2007
- Class 0: No Donation
- Class 1: Donation

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Imbalanced-learn
- Jupyter Notebook

## Data Preprocessing
- Dataset understanding and cleaning
- Missing-value and duplicate checking
- Exploratory Data Analysis
- Outlier analysis
- Skewness analysis
- Log transformation
- Feature scaling
- Train-test splitting

## Machine Learning Algorithms
1. Logistic Regression
2. K-Nearest Neighbors
3. Decision Tree
4. Random Forest
5. Support Vector Machine
6. Gaussian Naive Bayes
7. XGBoost

## Model Improvement Techniques
- Class weight balancing
- SMOTE
- GridSearchCV hyperparameter tuning

## Model Evaluation
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC

## Final Model
Original Random Forest was selected based on its F1-score for the donation class.

| Metric | Score |
|---|---:|
| Accuracy | 75% |
| Precision | 48% |
| Recall | 36% |
| F1-score | 41% |
| ROC-AUC | 0.655 |

## Conclusion
The project demonstrates how Machine Learning can be used to predict blood donation behaviour. It also highlights the challenges of imbalanced classification and the importance of evaluating models using multiple performance metrics.

## Future Scope
- Collect more donor data.
- Improve donor detection.
- Experiment with additional classification techniques.
- Develop a user-friendly prediction application.
