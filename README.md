## Titanic Survival Prediction
This project analyzes the Titanic dataset to predict passenger survival. Using Python and machine learning techniques, the project builds predictive models to identify which passengers were more likely to survive the disaster.

# Project Objective
The goal of this project is to:
- Explore and analyze passenger data, including age, sex, class, and other factors.
- Build predictive models to estimate the likelihood of survival.
- Combine multiple models using ensemble techniques to improve prediction accuracy.

# Dataset
- Source: [Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- Features include passenger information such as age, sex, ticket class, family size, and port of embarkation.
- Target variable indicates whether a passenger survived (1) or not (0).

# Tech Stack
- Python
- Pandas & NumPy for data manipulation
- Matplotlib & Seaborn for data visualization
- Scikit-learn for modeling and evaluation
- GridSearchCV for hyperparameter tuning

# Modeling Approach
- Data Preprocessing: Convert categorical variables to dummy variables, handle missing values, and scale numerical features.
- Model Selection: Logistic Regression, Decision Tree, Random Forest, Support Vector Classifier (SVC), and K-Nearest Neighbors (KNN) were evaluated.
- Hyperparameter Tuning: GridSearchCV was used to optimize model parameters.
- Ensemble Modeling: A Voting Classifier was built combining Logistic Regression, Decision Tree, and Random Forest for improved predictions.
- Evaluation: Models were evaluated using accuracy and precision

