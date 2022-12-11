# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
1) variables that provided a non-random amount of variance to the mpg values in the dataset were ground_clearance (pvalue = 5.77e-08) and vehicle_length (pvalue= 2.60e-12).
2) The slope of the linear model is not considered to be zero because the coefficient of the variables are not equal to 0
3) This linear model somewhate predict mpg of MechaCar prototypes effectively. R^2 = 0.7149 which means this model is about 71.49% accurate.

## Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. The total Summary shows that variance is under 100 which is acceptable (62.2), however the lot summary shows that lot 3 is over 100PSI (170) which is not acceptable.

![Total Summary](https://user-images.githubusercontent.com/111706055/206886173-95e5ea6e-4472-4f6a-8f87-2de2067e4899.png)

![Lot Summary](https://user-images.githubusercontent.com/111706055/206886176-253e9b63-9747-4368-a097-76f86e14c6d0.png)

## T-Tests on Suspension Coils

1) Looking at all lots - p value = 0.06 hence we cannot say its statistically different from the population mean of 1,500 PSI
2) Looking at LOT 1 - pvalue = 1 for LOT 1, hence no proof statistically different from the population mean of 1,500 PSI
3) Looking at LOT 2 - pvalue = 0.6 for LOT 2, hence no proof statistically different from the population mean of 1,500 PSI
4) Looking at LOT 3 - pvalue = 0.04 for LOT 3, hence we can say it is statistically different from the population mean of 1,500 PSI, Null Hypothesis is rejected.

LOT 3 seems to have some issues and need to be expected to meet the necessary standards

## Study Design: MechaCar vs Competition
