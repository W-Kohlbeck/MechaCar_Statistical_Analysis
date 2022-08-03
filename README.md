# MechaCar_Statistical_Analysis

Approached by upper management about a special project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

In this challenge, you’ll help the data analytics team do the following:

1. Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes.
2. Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
3. Run t-tests to determine if the manufacturing lots are statistically different from the mean population
4. Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

## Linear Regression to Predict MPG

1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
- As displayed in the summary of linear regresion below it was found that the vehicle length and ground clearence had a significant non random amount of variance. In turn meaning that they play a big factor on the MPG a vehicle may obtain.

2. Is the slope of the linear model considered to be zero? Why or why not?
- With a p-value: 5.35e-11 the slope of the linear model is not considered to be close to zero as it ios well beyond the pvalue goal of 0.05.

3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
- With an r-value of 0.7149 it demonstrates a strong correlation in predicting mpg of MechaCar prototypes.

<img width="801" alt="image" src="https://user-images.githubusercontent.com/102195085/182500248-dec40076-5eeb-4a18-a7d7-af364a62ca64.png">

## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

### Total Summary
<img width="463" alt="image" src="https://user-images.githubusercontent.com/102195085/182504054-2aa329fb-c577-415f-835a-e948c2e40caf.png">

When looking at the above results the total of all suspension coils has a variance PSI of 62.29356 which is well within the 100 PSI reqquirement.

### Lot Summary
<img width="602" alt="image" src="https://user-images.githubusercontent.com/102195085/182504216-c9875ebb-62ff-4513-ad8a-49a8378fd02a.png">

The picture changes a bit when we compare the three lots individaully. As seen above lot 1 and lot 2 are well withing the variance standard. Lot 3 however is well outside the standard variance with a 170.2861224.

## T-Tests on Suspension Coils

<img width="828" alt="image" src="https://user-images.githubusercontent.com/102195085/182506407-4f59f01b-da5e-4095-8e40-45965c9469f8.png">

## Study Design: MechaCar vs Competition
Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.

In your description, address the following questions:
What metric or metrics are you going to test?
What is the null hypothesis or alternative hypothesis?
What statistical test would you use to test the hypothesis? And why?
What data is needed to run the statistical test?
