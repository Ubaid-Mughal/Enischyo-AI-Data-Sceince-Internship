Week 3 : Student Performance Prediction
Objective: Build a machine learning model to predict whether a student will pass or fail based on demographic, social and academic attributes.
Dataset: UCI Student Performance Dataset (Math course), 649 rows, 33 columns. Source: https://www.kaggle.com/datasets/larsen0966/student-performance-data-set
Models Used: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting
Results:
Gradient Boosting was the best model with 92% accuracy, 95.5% F1-score and 0.97 ROC-AUC. GridSearchCV hyperparameter tuning was applied with best parameters learning_rate=0.3, max_depth=3, n_estimators=100.
Key Findings:
total_grade (G1+G2 combined) was the strongest predictor at 0.73 importance score. Past failures is the biggest risk factor for failing. Alcohol consumption negatively impacts student performance. Dataset is imbalanced with 85% passing students so F1 and AUC were prioritized over accuracy.
Steps Completed:
EDA with class balance check, correlation analysis and boxplots. Feature engineering with 2 derived features. Label encoding and get dummies for categorical columns. StandardScaler for numerical features. 80/20 train test split with stratify. 4 models trained and compared. Confusion matrix, feature importance and ROC curves plotted. GridSearchCV hyperparameter tuning. 400 word model evaluation report written.
