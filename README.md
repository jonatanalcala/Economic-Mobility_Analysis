# Economic-Mobility_Analysis

## Project Overview

This project investigates economic mobility trends across different regions in the United States. The analysis explores various socioeconomic factors, including family structure, commute times, income inequality, and racial demographics, to understand their impact on social mobility. A linear regression model was developed to identify the most influential predictors.

## Methodology

1. **Exploratory Data Analysis (EDA)**:
   - Conducted bi-variate and multi-variate analyses to identify key variables.
   - Addressed missing values, collinearity, and heteroscedasticity issues.

2. **Model Creation**:
   - Used stepwise selection based on AIC to choose the best predictive variables.
   - Applied transformations (e.g., reciprocal, squared) to improve linear model assumptions.
   - Addressed heteroscedasticity and multicollinearity.

3. **Final Model**:
   - Key predictors: Single Motherhood, Commute, Middle Class.
   - Performance metrics:
     - Train Adjusted R²: 0.70
     - Test R²: 0.71
     - Test RMSE: 0.03
     - Test MAE: 0.02

4. **Regional Performance**:
   - The model performed well across most regions except for the Northeast, likely due to fewer data points.

## Key Findings

- Higher single motherhood rates correlate with lower mobility.
- Shorter commute times improve economic opportunities.
- The strength of the middle class positively impacts mobility.
- Income inequality (Gini coefficient) limits upward mobility.
- Education-related factors had a high rate of missing values and were excluded from the final model.

## Future Improvements

- Collect more complete education-related data.
- Improve model generalization for the Northeast region.
- Explore non-linear models or machine learning approaches for better accuracy.
