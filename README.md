# data-science-internship-tasks

## Task 1: Exploring and Visualizing the Iris Dataset

### Objective
Load, inspect, and visualize the Iris dataset using pandas,
matplotlib, and seaborn to understand data structure and patterns.

### Approach
1. Loaded the dataset using seaborn's built-in loader
2. Inspected structure using .shape, .columns, and .head()
3. Created scatter plots, histograms, and box plots

### Results and Insights
- The Iris dataset has 150 rows and 5 columns (4 features + 1 target)
- Setosa species is visually separable from versicolor and virginica
- Petal measurements are more useful for distinguishing species
- A few outliers were detected in sepal width for setosa

### Tools Used
- Python, pandas, matplotlib, seaborn, Jupyter Notebook

  
------------------------------------------------------------------------------------
## Task 4: Predicting Insurance Claim Amounts

### Objective
Linear Regression se insurance charges predict karna

### Approach
1. insurance.csv dataset load kiya
2. Missing values check kiye — dataset clean tha
3. sex, smoker, region columns encode kiye
4. Linear Regression model train kiya (80/20 split)
5. MAE aur RMSE se evaluate kiya

### Results
- Smoking sabse bada factor nikla (0.79 correlation)
- Model R2 Score: ~0.78
- MAE: ~$4,200

### Tools Used
Python, pandas, matplotlib, seaborn, scikit-learn

-----------------------------------------------------------------------------------

## Task 5: Personal Loan Acceptance Prediction

### Objective
Predict which bank customers are likely to accept a personal loan offer using classification modeling.

### Approach
1. Loaded Bank Marketing Dataset (bank-additional-full.csv) — 41,188 rows, 21 columns
2. Checked missing values — dataset was clean
3. Encoded all categorical columns using Label Encoding
4. Performed EDA — analyzed age, job type, call duration, and marital status
5. Trained Decision Tree Classifier (max_depth=5, 80/20 split)
6. Evaluated using accuracy score, confusion matrix, and classification report
7. Extracted feature importance to identify key drivers

### Results and Insights
- Model Accuracy: ~85%
- Call duration is the strongest predictor of loan acceptance
- Only 11.27% customers accepted — dataset is heavily imbalanced
- Longer phone calls strongly correlate with higher acceptance rates
- Retired and student job types show higher acceptance rates

### Tools Used
Python, pandas, matplotlib, seaborn, scikit-learn, Jupyter Notebook
