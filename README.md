# Titanic Survival Prediction using Machine Learning #
# Project Description

This project analyzes the Titanic dataset and builds predictive models to determine whether a passenger survived the Titanic disaster or not.
The goal is to preprocess the data, detect and handle outliers, encode categorical variables, and train multiple classification models to find the best-performing one.

# Objectives

- Explore, clean, and preprocess Titanic passenger data.

- Handle missing values and outliers.

- Encode categorical features into numeric form.

- Build and compare multiple machine learning models:

- K-Nearest Neighbors (KNN)

- Naive Bayes (GaussianNB)

- Support Vector Machine (SVM)

- Evaluate models using accuracy, precision, recall, and F1-score metrics.

- Identify the best-performing algorithm for survival prediction.

# Tools & Libraries

- Python

- Pandas, NumPy – for data handling and analysis

- Seaborn, Matplotlib – for data visualization

- Scikit-learn (sklearn) – for machine learning models and evaluation

- SciPy, Collections – for statistics and outlier detection

# Dataset

The dataset includes information about Titanic passengers such as:

- pclass – Passenger class (1st, 2nd, 3rd)

- name – Passenger name

- sex – Gender (male/female)

- age – Age of the passenger

- sibsp – Number of siblings/spouses aboard

- parch – Number of parents/children aboard

- ticket – Ticket number

- fare – Ticket price

- embarked – Port of Embarkation (S, C, Q)

- survived – Survival (1 = Yes, 0 = No)

# Data Preprocessing Steps

- Filled missing age values with the mean.

- Removed remaining missing and duplicate rows.

- Converted categorical variables (sex, embarked) to numeric values.

- Detected and removed outliers using the Interquartile Range (IQR) method.

- Split the dataset into training (80%) and testing (20%) subsets.

# Machine Learning Models
1️⃣ K-Nearest Neighbors (KNN)

- Tested different k values and distance metrics (Euclidean, Manhattan, Chebyshev).

- Tuned k for best performance.

- Accuracy: 60 %

2️⃣ Gaussian Naive Bayes (GNB)

- Simple probabilistic model assuming feature independence.

- Accuracy: 75%

- Achieved best results with optimal parameters.

3️⃣ Support Vector Machine (SVM)

- Trained using multiple kernel functions (linear, rbf, poly).

- Applied GridSearchCV for hyperparameter tuning.

- Accuracy: 62%
  

# Key Insights

- Gender (Sex) and Passenger Class (Pclass) are strong indicators of survival.

- Females and 1st-class passengers had higher survival rates.

- Outlier removal improved overall model performance.

- Naive Bayes achieved the best overall accuracy among all tested models.
