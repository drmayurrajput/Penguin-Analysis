# Penguin Analysis

This project explores the characteristics of penguins using R programming. It includes data visualization, summary statistics, and regression analysis to understand the relationships between penguin features.

-The regression analysis aimed to model the relationship between the dependent variable billLengthCm and the independent variables billWidthCm, flipperLengthCm, and flipperWidthCm. The results are as follows:

Coefficients:
-Intercept (1.84506): The intercept represents the estimated value of billLengthCm when all independent variables are zero. In this context, it may not have a practical interpretation.

-billWidthCm (0.65486): For every one-unit increase in billWidthCm, there is an estimated increase of 0.65486 units in billLengthCm, holding other variables constant. This suggests a positive linear relationship between bill length and width.

-flipperLengthCm (0.71106): For every one-unit increase in flipperLengthCm, there is an estimated increase of 0.71106 units in billLengthCm. This implies that penguins with longer flippers tend to have longer bills.

-flipperWidthCm (-0.56257): For every one-unit increase in flipperWidthCm, there is an estimated decrease of 0.56257 units in billLengthCm. This suggests a negative association, indicating that penguins with wider flippers tend to have shorter bills.

Statistical Significance:
All coefficients are statistically significant with very low p-values (< 0.001), providing strong evidence against the null hypothesis that the corresponding coefficients are equal to zero.

-Model Fit: Residuals: The residuals (differences between observed and predicted values) have a small spread, indicating a good fit of the model to the data.

-R-squared (0.8592): The R-squared value is 0.8592, indicating that approximately 85.92% of the variability in billLengthCm can be explained by the model. This suggests a strong predictive power of the model.

-Adjusted R-squared (0.8563): The adjusted R-squared, accounting for the number of predictors, is 0.8563.

-F-statistic: The F-statistic tests the overall significance of the regression model. The obtained F-statistic is 297 with a very low p-value (< 2.2e-16), indicating that the model is statistically significant.

Conclusion:
-The regression model suggests that billWidthCm, flipperLengthCm, and flipperWidthCm are all significant predictors of billLengthCm. The model provides a good fit to the data, explaining a substantial portion of the variability in billLengthCm. The positive coefficients for billWidthCm and flipperLengthCm suggest positive associations, while the negative coefficient for flipperWidthCm suggests a negative association with billLengthCm. The overall model is highly significant and demonstrates good explanatory power.

### Output
![RBilllengthcmandwidth](https://github.com/drmayurrajput/Penguin-Analysis/assets/151954348/4a1c83d2-4bfc-4938-bf2a-3ccb05d93f82)
![FlipperLengthCMandwidth](https://github.com/drmayurrajput/Penguin-Analysis/assets/151954348/206757db-c813-4863-9aa4-0889dc2004f8)


## Dependencies

- ggplot2
- tidyr
- dplyr
