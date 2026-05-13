# Spotify Song Preference Classification using Machine Learning

## Project Overview
This project predicts whether a Spotify song will be liked or not based on its audio features using supervised machine learning classification models.

The objective was to compare multiple classification algorithms, evaluate model performance, diagnose overfitting, and perform hyperparameter tuning for model optimization.

---

## Dataset Features
The dataset includes Spotify audio characteristics such as:

- danceability
- energy
- key
- loudness
- mode
- speechiness
- acousticness
- instrumentalness
- liveness
- valence
- tempo
- duration_ms
- time_signature

Target Variable:
- liked (0 = Not Liked, 1 = Liked)

---

## Project Workflow
### Data Preprocessing
- Data loading and inspection
- Null value check
- Duplicate check
- Column name standardization
- Invalid value handling
- Feature-target separation
- Train-test split
- Feature scaling (where required)

---

## Exploratory Data Analysis
- Target balance analysis
- Outlier inspection
- Correlation heatmap
- Multicollinearity reasoning

---

## Models Implemented
- Logistic Regression
- Decision Tree Classifier
- Tuned Decision Tree
- Random Forest Classifier
- Support Vector Machine (RBF Kernel)
- XGBoost Classifier

---

## Model Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Cross Validation
- GridSearchCV Hyperparameter Tuning

---

## Key Findings
- Logistic Regression achieved strong baseline performance.
- Decision Tree initially overfit and was improved through hyperparameter tuning.
- Random Forest, SVM, XGBoost, and Logistic Regression achieved comparable strong performance.
- Feature importance analysis identified instrumentalness, speechiness, and danceability as strong predictors.

---

## Best Model Performance
Accuracy: ~92.3%

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## Business Interpretation
This type of classification can support:
- personalized music recommendation systems
- playlist curation
- listener preference prediction
- music behavior analytics
