
# Data Science Learning
This repository contains my daily practice and learning of **Data Science using Pandas**.

## 📅 Day-wise Progress

### Day 3 – Sorting & GroupBy
- Learned sorting data using `sort_values()`
- Used `groupby()` for data aggregation
- Performed basic analysis on tabular data

### Day 4 – Data Cleaning
- Handling missing values using `dropna()`
- Understanding `df.info()` and data types
- Basic data cleaning techniques in Pandas

### Day 5 – Exploratory Data Analysis (EDA)
- Performed basic EDA using Pandas
- Used `describe()` for statistical summary
- Analyzed marks distribution
- Visualized data using Matplotlib (histogram, bar chart, line plot)
- Derived basic insights from data

## Day 8 – Machine Learning
- Built a Linear Regression model
- Predicted writing score using math & reading scores
- Evaluated model using Mean Absolute Error (MAE)

## Day 09 0r 10 – Student Performance Prediction (ML)
### Objective
Build a machine learning model to predict students' writing scores based on academic and demographic features.
### Model Used
- Linear Regression
### Evaluation Metrics
- Mean Squared Error (MSE): ~23.66
- R² Score: ~0.90

### Day 11 – Decision Tree Regression
- Objective: Predict writing score
- Algorithm: Decision Tree Regressor
- Features used: math score, reading score
- Evaluation metrics: MAE, R² Score
- Overfitting handled using max_depth

  ## Day 12 – Random Forest Regression
- Implemented Random Forest Regressor
- Compared performance using MAE and R2 Score
- Analyzed feature importance
- Observed reading score as the most influential feature

###Day 13 – Model Evaluation & Comparison**
- Train R² > Test R²
- Decision Tree:more overfit hota hai
- Random Forest:stable & accurate
- Random Forest > Decision Tree

 ### Day 14 – Hyperparameter Tuning
- Applied GridSearchCV on Random Forest Regressor
- Tuned parameters: n_estimators, max_depth, min_samples_split, min_samples_leaf
- Model performance improved after tuning
- MAE decreased and R² score increased
- Overfitting reduced and generalization improved

 ### Day 15 – End-to-End Machine Learning Project
- Dataset: Student Performance
- Target: Writing Score Prediction
- Model Used: Random Forest Regressor
- Evaluation Metrics: MAE, R² Score
**Results
MAE ≈ 4.25
R² Score ≈ 0.88
**Key Insight
Reading score is the most important feature.
Model generalizes well, no major overfitting

### Visualization
The scatter plot of **Actual vs Predicted Writing Score** shows that most points lie close to the diagonal line, indicating that the model predictions are very close to the actual values and the model performs well.
### Conclusion
1.The model successfully learns the relationship between input features and writing scores and provides accurate predictions.
2.The model performs well as residuals are randomly distributed around zero.
MAE value shows the average prediction error is low.

## 📊 Dataset
- Source: Student Performance Dataset
- Features: gender, parental education, reading score, math score
- Target Variable: writing score


## 🛠 Tools Used
- Python
- Pandas
- Jupyter Notebook
- GitHub
- Matplotlib
- Seaborn
- Numpy
- Scikit learn

## Skill Covering
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Selection
- Machine Learning Model Training
- Regression Models
- Model Evaluation (MAE, R²)
- Overfitting Detection
- Hyperparameter Tuning

  ## 🤖 Model Summary
- Algorithm: Random Forest Regressor
- MAE: Low (good prediction accuracy)
- Residuals: Randomly distributed
- Overfitting: No (train & test performance similar)



## 🚀 Goal
To build a strong foundation in **Data Science** through daily hands-on practice.

## 🚀 Future Improvements
- Try XGBoost and Gradient Boosting
- Deploy model using Streamlit

---
✨ Learning step by step, one day at a time.









