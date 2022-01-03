# MechaCar_Statistical_Analysis
 
## Linear Regression to Predict MPG

A multiple linear regression was run against the data set. All six categories were evaluated (vehicle_length, vehicle_weight, spoiler_angle, ground_clearance, AWD). The results were as follows:

![Linear Regression MPG](/images/lin_regress_mpg.PNG)

The R-squared value is 0.715 and the P-value is smaller than than the assumed significance of 0.05. There is sufficient evidence to reject our null hypothesis, which means that the slope of our linear model is not zero.

The primary contributing categories are ground clearance and vehicle length. The linear model does predict MPG effictively as the correlations are statistically significant. Additional categories may provide more accurate results.

## Summary Statistics on Suspension Coils

The suspension coil data set was analyzed to show:

    - The suspension coil’s PSI continuous variable across all manufacturing lots
    - The following PSI metrics for each lot: mean, median, variance, and standard deviation.

The results are:
#### Statistics Across All Lots
![Stats Across Lots](/images/stats_across_lots.PNG)

#### Statistics Per Lot
![Stats Across Lots](/images/stats_per_lot.PNG)

In total, the variance is withing the manufacturing limit of a 100 PSI variance. However, per lot variance is not acceptable. Lot 3 is out of specification and should be rejected.

## T-Tests on Suspension Coils

T-Tests were run across all lots and for each lot to determine if the PSI values are statistically different from the population.

Here are the results:

#### T-Test for all lots - from a sample of 50
![Stats Across Lots](/images/ttest_all.PNG.PNG)

The P-Value is above 0.05 and the mean is 1499.02. The PSI values are not statistically different

#### T-Test for Lot1
![Stats Across Lots](/images/ttest_lot1.PNG)

The P-Value is lower than 0.05 and the mean is 1500. The PSI values are statistically different.

#### T-Test for Lot1
![Stats Across Lots](/images/ttest_lot2.PNG)

Similar to lot 1, the P-Value is lower than 0.05 and the mean is 1500.02. The PSI values are statistically different.

#### T-Test for Lot3
![Stats Across Lots](/images/ttest_lot3.PNG)

Here the P-Value is above 0.05 and the mean is 1496.14. The PSI values are statistically different.