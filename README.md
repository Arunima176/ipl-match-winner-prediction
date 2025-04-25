🏏 **IPL Match Winner Prediction Using Machine Learning**

📌 **Overview**

This project focuses on predicting the outcome of Indian Premier League (IPL) matches using supervised machine learning techniques. The goal is to build and compare multiple models, fine-tune the best one, and identify the most accurate predictor of match results.

📊 **Dataset**

The dataset includes historical match-level data from multiple IPL seasons.
Key features:


Teams (team1, team2)

Toss winner and decision

Venue and city

Match result, win margin

Player of the match

Umpires

Duckworth-Lewis indicator

🔧 **Data Preprocessing**

✅ Standardized data types

✅ Handled missing values

✅ Removed duplicates

✅ Outlier detection and removal

✅ Feature engineering for improved model performance

🔄 **Data Transformation**

Label Encoding: Converted all categorical variables (e.g., team names, cities, result, etc.) into numeric format

Feature Scaling: Used StandardScaler to normalize features for improved accuracy

🤖 **Machine Learning Models Used**

Several supervised machine learning algorithms were trained and evaluated:

Logistic Regression

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Decision Tree

Random Forest

XGBoost Classifier

🔍 **Hyperparameter Tuning**

Used GridSearchCV to tune the Decision Tree model:

Best parameters:

criterion = 'entropy'

max_depth = 15

min_samples_leaf = 1

Accuracy improved from:

Initial: 90%

Cross-validation: 92%

Test accuracy: 96%

🏆 **Best Performing Model**

The XGBoost Classifier achieved:

🔹 Highest Accuracy: 98%

🔹 Best Precision & Recall

✅ Robust and reliable for classification

📈 **Conclusion**

This project demonstrates how advanced ML techniques and proper preprocessing can effectively predict the outcomes of IPL matches.
XGBoost stood out as the most accurate and consistent model, making it the ideal choice for real-world match prediction scenarios.

💻 **Tools & Libraries**

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

XGBoost

Jupyter Notebook
