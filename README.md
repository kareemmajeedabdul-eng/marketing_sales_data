  marketing_sales_data
Overview Multiple Linear Regression – Multi-Channel Marketing Analysis Project Overview In this project, you will analyze a marketing dataset using Python and statsmodels to build a Multiple Linear Regression model. 

The Adjusted R-squared value of 0.903 indicates that approximately 90.3% of the variation in Sales can be explained by the marketing variables included in the model. This suggests that the model has very strong predictive power and provides a good fit for the data.

Social Media advertising and Influencer categories do not show statistically significant effects on Sales in this model because their p-values are greater than 0.05.

Business Interpretation

Holding all other variables constant, a one-unit increase in Radio advertising spend is associated with an increase of approximately 2.97 units in Sales.

This is a positive effect.

Holding all other variables constant, campaigns in the TV_Low category generate approximately 154.57 fewer Sales units compared to the TV_High category.

Holding all other variables constant, campaigns in the TV_Medium category generate approximately 75.59 fewer Sales units compared to the TV_High category.

Diagnostic Interpretation
Linearity

The residual plots indicate that the relationship between predictors and Sales is reasonably linear.

Normality

The QQ plot shows that residuals generally follow the expected normal distribution pattern, with only minor deviations.

Homoscedasticity

Residuals appear randomly scattered around zero, suggesting that the variance of residuals remains relatively constant across predicted values.

Final Business Recommendation

This is the most important section.

Recommendation

Based on the multiple linear regression analysis, TV advertising and Radio advertising are the strongest drivers of Sales. The model explains approximately 90.3% of Sales variation, indicating a highly reliable relationship between marketing activities and business outcomes.

TV advertising should receive the highest priority because the TV_High category consistently outperforms both TV_Medium and TV_Low categories. Radio advertising should also be prioritized because it has a positive and statistically significant effect on Sales.

Social Media and Influencer marketing variables were not statistically significant in this analysis. Therefore, management should consider allocating a larger portion of the marketing budget to TV and Radio campaigns while reassessing the effectiveness of Social Media and Influencer investments.
