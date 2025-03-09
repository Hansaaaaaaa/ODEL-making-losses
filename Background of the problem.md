This code explores the factors which contributes to ODEL's losses by utilising predictive modelling techniques. The analysis begins with data preprocessing, including handling missing values and inconsistent data by removing rows with NA values. It proceeds with multiple linear regression to assess the impact of various financial and operational variables on the dependent variable, Loss for the Year.

Key steps include:

Multicollinearity Check: Variance Inflation Factor (VIF) is used to identify multicollinearity among predictors.
Stepwise Regression: The stepAIC method is applied for both forward and backward selection to refine the regression model.
Model Diagnostics: The code checks for aliasing issues and ensures predictors have adequate variance.
Prediction and Visualization: It generates predictions, scales them for comparison, and plots actual vs. predicted losses.
Random Forest Model: To enhance predictive accuracy, a random forest model is built, with variable importance assessed and visualized using a variable importance plot.
This comprehensive approach helps identify the key drivers of losses, providing actionable insights for reducing financial deficits
