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
- With a p-value: 5.35e-11 the slope of the linear model is not considered to be close to zero as it is well beyond the p-value goal of 0.05.

3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
- With an r-value of 0.7149 it demonstrates a strong correlation in predicting mpg of MechaCar prototypes.

<img width="801" alt="image" src="https://user-images.githubusercontent.com/102195085/182500248-dec40076-5eeb-4a18-a7d7-af364a62ca64.png">

## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

### Total Summary
<img width="463" alt="image" src="https://user-images.githubusercontent.com/102195085/182504054-2aa329fb-c577-415f-835a-e948c2e40caf.png">

When looking at the above results the total of all suspension coils has a variance PSI of 62.29356 which is well within the 100 PSI requirement.

### Lot Summary
<img width="602" alt="image" src="https://user-images.githubusercontent.com/102195085/182504216-c9875ebb-62ff-4513-ad8a-49a8378fd02a.png">

The picture changes a bit when we compare the three lots individaully. As seen above lot 1 and lot 2 are well withing the variance standard. Lot 3 however is well outside the standard variance with a 170.2861224.

## T-Tests on Suspension Coils
Performing t-tests to determine if all manufacturing lots and each lot individually are statistically different from the population mean of 1,500 pounds per square inch we can confirm further the information found in the summary statistics.

When looking at the lots as a whole the mean of all suspension PSI's came in at 1498.78 and a p-value of 0.06028. This would indicate that there is no signifacant reason to reject the hypothesis. 

Looking further at each individual lot we see that lot 1 and lot 2 follow suit of the whole lot with a p-value of 1 and 0.6072 respectively. However looking at lot 3 the p-value comes in at 0.04168 which would indicate a significant proability that the hypothesis would fail and not meat the 1,500 PSI needed.

<img width="828" alt="image" src="https://user-images.githubusercontent.com/102195085/182506407-4f59f01b-da5e-4095-8e40-45965c9469f8.png">

## Study Design: MechaCar vs Competition
Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer.

When consumers want to compare vehicles and features there may be a high demand to compare price and reliability. In order to do so we would want to compare similarly constructed vehicles to that of MechaCar from multiple manufacturers.

In order to do so the metrics to be looked at will include vehicle MSRP and reliability from like vehicles over the last 2 years.

Hypothesis
Null hypothesis: MechaCar will perform higher than alternatives in regards to price and reliability.
Alternative hypothesis: MechaCar will under perform alternatives in regards to price and reliability.

In order to perform this analysis, multiple linear regresion would be performed to compare vehicle price and reliability. In order to do so we would need to get MSPR pricing and reliability reports for all like vehicles among different manufacturers.
