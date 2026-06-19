<img width="574" height="453" alt="qq plot of residuals" src="https://github.com/user-attachments/assets/a9b3f12a-0e35-4f74-a8ed-8f214715b6b0" />

<img width="699" height="468" alt="residual plot" src="https://github.com/user-attachments/assets/3d6bb766-d204-401b-a9a6-97eb03b6e792" />




Multiple Linear Regression – Multi-Channel Marketing Analysis

Project Overview

This project uses Multiple Linear Regression to analyze the impact of various marketing channels on Sales. The objective is to determine which marketing activities contribute most significantly to sales performance and provide data-driven recommendations for budget allocation.

Dataset

The dataset contains the following variables:

* TV
* Radio
* Social Media
* Influencer
* Sales

Objectives

* Perform exploratory data analysis
* Check for missing values
* Detect multicollinearity using Correlation Matrix and VIF
* Build a Multiple Linear Regression model using statsmodels
* Evaluate model performance using Adjusted R-squared and p-values
* Validate model assumptions using diagnostic plots
* Provide business recommendations based on model results

Tools Used

* Python
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Statsmodels

Environment Setup

```bash
pip install pandas numpy seaborn matplotlib statsmodels
```

Methodology

1. Loaded and explored the dataset.
2. Checked for missing values.
3. Converted categorical variables into dummy variables.
4. Performed correlation analysis.
5. Calculated Variance Inflation Factor (VIF).
6. Built a Multiple Linear Regression model using OLS.
7. Generated residual and QQ plots to validate assumptions.
8. Interpreted coefficients, Adjusted R-squared, and p-values.

Results

* Adjusted R-squared: 0.903
* F-statistic: 760.4
* Radio advertising was statistically significant.
* TV advertising showed strong influence on Sales.
* Social Media and Influencer variables were not statistically significant.

* Final Regression Equation

Sales =
217.4784
+ 2.9735(Radio)
- 0.1391(Social Media)
-154.5736(TV_Low)
-75.5947(TV_Medium)
+2.4948(Influencer_Mega)
+2.9391(Influencer_Micro)
+0.8015(Influencer_Nano)

Business Recommendation

The analysis indicates that TV and Radio advertising should be prioritized because they demonstrate the strongest impact on Sales. Social Media and Influencer campaigns showed limited statistical significance and should be reviewed before receiving additional budget allocation.
