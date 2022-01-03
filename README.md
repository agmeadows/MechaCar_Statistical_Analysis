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