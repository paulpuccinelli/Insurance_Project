## US Medical Insurance Cost Analysis  
This project explores patterns in U.S. medical insurance charges using Python and basic statistical modeling techniques. The goal is to investigate how factors such as smoking status, region, and demographic variables relate to insurance premiums, 
and to demonstrate core data analysis and regression modeling skills.  
#### Project overview  
Using the *insurance.csv* dataset, the notebook:
- Loads and explores insurance data.
- Examines regional differences in insurance charges.
- Analyzes regional variation in smoking prevalence.
- Compares regional premiums with national averages.
- Manually implements a multiple linear regression mondel.
- Verifies results using statsmodels *sm.OLS*.
- Evaluates model preformance using residual analysis.
 
The project emphasizes understanding the mechanics of regression rather than relying solely on high-level libraries.  
#### Dataset
The dataset contains individual-level insurance information, including:
- Age
- Sex
- BMI
- Number of children
- Smoking status
- Region
- Medical insurance charges

#### Methods Used
- Data cleaning and transformation
- One-hot encoding of categorical variables
- Grouped aggregation and summary statistics
- Manual construction of regression design matrix
- Closed-form OLS solution:  
  $$\beta=(X^TX)^{-1}X^TY$$
- Regression validation using statsmodels
- Residual analysis for model diagnostics

#### Key Findings
- Regions with higher smoking prevalence tend to have higher average insurance premiums.
- A linear regression model captures broad charge patterns but shows signs of:
  - Heteroskedasticity
  - Model misspecification
  - Non-random residual structure

This suggests more sophisticated modeling could improve predictions.  
#### Tools and Libraries
- Python
- Pandas
- Numpy
- Matplotlib
- Statsmodels

#### Future Improvements  
Potential extensions include:
- Regularized regression models
- Nonlinear models or interactions
- Cross-validation and test error estimation
- Feature engineering
- Larger or richer datasets

#### Author
Paul Puccinelli   
Statistics & Economics, UC Berkeley
