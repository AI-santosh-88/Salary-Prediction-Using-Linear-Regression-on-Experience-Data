# Title: - "Salary Prediction Using Linear Regression on Experience Data"

## Business Use Case:
### Problem:
 Company wants to estimate employee salaries based on their experience to assist with budgeting, HR planning, and fair compensation strategies.
* Solution:
Use historical data to create a linear regression model that predicts salaries accurately. This helps:
* Set salary expectations for new hires.
* Benchmark employee pay.
* Make data-driven compensation decisions.
* Outcome:
With an R² score of 0.974, the model explains ~97.4% of the salary variance using experience alone. This high level of accuracy can be extremely useful in real-world HR analytics scenarios.

## Description: 
* project explores a simple linear regression model to predict salaries based on years of professional experience. The dataset contains only two variables — Years of Experience and Salary — making it a classic and intuitive example of a univariate regression problem. The objective is to build a predictive model that accurately estimates salary, validate its performance, and test the core assumptions of linear regression.

## Responsibilities:
1.Data Exploration:
* Loaded and visualized the dataset.
* Checked for null values, outliers, skewness, and kurtosis.
* Analyzed statistical properties using .describe().
2.Data Visualization:
* Plotted pairwise plots, heatmaps, line plots, and scatter plots.
* Visualized the correlation between features.
3.Model Development:
* Split data into training and test sets.
* Applied Linear Regression using sklearn.linear_model.
* Trained the model and obtained regression coefficients.
4.Model Evaluation:
* Evaluated performance using R², MAE, MSE, and RMSE.
* Interpreted the regression line equation: Salary = β0 + β1 * YearsExperience.
5.Assumption Testing:
* Verified key regression assumptions:
* Linearity
* Normality of residuals
* Homoscedasticity
* No autocorrelation (using ACF plot)
* No multicollinearity (only 1 feature here, so N/A)

## Libraries:
Library	Purpose
1.pandas -	Data loading and manipulation
2.numpy - 	Mathematical operations
3.matplotlib- Data visualization
4.seaborn	- Statistical plotting and heatmaps
5.sklearn - Linear regression modeling and evaluation
6.statsmodels - Statistical tests (ACF, assumptions checking)
7.warnings- Ignore unimportant warnings

## Summary:
* A linear regression model was developed to predict Salary based on Years of Experience.
* The dataset had 30 entries and showed a strong correlation (0.978) between the variables.
* The final model achieved:
* R² Score: 0.974
* MAE: ~3737
* RMSE: ~4834
* Regression assumptions were tested and confirmed (linearity, normality, homoscedasticity, etc.).
* This project showcases how basic statistical modeling can support HR and compensation planning using minimal data but strong methodology.






