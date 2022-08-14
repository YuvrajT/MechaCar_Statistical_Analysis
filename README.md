# MechaCar Statistical Analysis

## Overview:

To perform satatistical analysis on MechaCar protoypes dataset, to identify/establish realtionship between the different variables to mpg.

## Deliverable 1

### Linear Regression to Predict MPG

Based on the results(images) below:

- There are no variables that provide a non-random amount of variance to MPG values in that dataset. Since the value of pr(>|t|) is greater than .05, thus it has no significant impact of MPG values. Therefore, we can reject the null hypothesis. 

- The slope is not considered to be zero because all vairables are directly proportional to mpg values. 

- The liner model does not predict MPG effectively beacuse P value of the multiple linear regression test is 5.35e-11 which is higher than .05. 

![](https://github.com/YuvrajT/MechaCar_Statistical_Analysis/blob/main/Resources/lm.png)

## Deliverable 2

### Summary Statistics on Suspension Coils

Based of the results(images) below:

- As per the total summary the vairance of suspension coils in under 100 but when we look at the lot summary, clearly the lot 3 has the varriance over 100. 
- Thus the current manufacturing data does not meet the design specification for lot 3. 

![](https://github.com/YuvrajT/MechaCar_Statistical_Analysis/blob/main/Resources/total_summary.png)

![](https://github.com/YuvrajT/MechaCar_Statistical_Analysis/blob/main/Resources/lot_summary.png)

## Deliverable 3

### T-Tests on Suspension Coils

**To determine if PSI across all manufacturing lots is satistical different from the population mean of 1500 pounds per square inch**

- As per the test result below, the P value is 1 which is greater than 0.05, thus there is no satistical difference and we fail to reject the null hypothesis. 

![](https://github.com/YuvrajT/MechaCar_Statistical_Analysis/blob/main/Resources/all_lots.png)

**To determine if PSI for each manufacturing lots is satistical different from the population mean of 1500 pounds per square inch**

- As per the test results below: for lot 1 the P value is 1.568e-11 which is greater than .05, thus there is no satistical difference and we fail to reject the null hypothesis. 

- For Lot 2, the P value is 0.00005911 which is less than 0.05, thus there is satistical difference and we reject the null hypothesis. 

- For Lot 3, the P value is 0.1589 which is greater than 0.05, thus there is no satistical difference and we fail to reject the null hypothesis. 

![](https://github.com/YuvrajT/MechaCar_Statistical_Analysis/blob/main/Resources/each_lot.png)

## Deliverable 4:

### Study Design: MechaCar vs Competition:

There are multiple factors that MechaCar can use and perform analysis against the competetion: safety rating, cost, highway and city fuel efficienty, maintiance, horse power, seating capacity, PSI, ground clearence. 

1. We can perform analysis on safety rating and cost. Since these variable are very important and are highly considered by a consumer when buying a car, our test can justify the cost associated for the MechaCars

2. Null Hypothesis: If the cost of the car cost is less than  CAD $15,000.00 the safety rating is average.
Alternate Hypothesis: If the cost of the car is not less than CAD $15,000.00 the safety rating is above average.

3. After setting up the null and alternate hypothesis, we can run test given we all the data required. If the test results in P value less than 0.05 we will conculde by saying we fail the null hypothesis, thus car prices less than CAD $15,000.00 does not have a safety rating of average. Whereas, on the other hand if t.test results in P value greater than 0.05 we can say car prices not less then CAD $15,000.00 have an above average safety rating. 

4. The dataset required to run satistical test: 

- The mean of both samples.
- The standard deviation of both samples.
- The median of both samples .
- The varrince of both samples. 
 
