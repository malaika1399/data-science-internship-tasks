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
