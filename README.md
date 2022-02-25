# MechaCar_Statistical_Analysis

A few weeks after starting his new role, Jeremy is approached by upper management about a special project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

In this challenge, we are helping Jeremy and the data analytics team do the following:

* Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
* Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
* Run t-tests to determine if the manufacturing lots are statistically different from the mean population
* Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

## Deliverable 1: Linear Regression to Predict MPG
1: Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

![Summary Linear Regression](https://user-images.githubusercontent.com/93050682/155798234-c10d7828-7867-4a58-88d9-da774ed27c81.PNG)

From the picture added above its colear that there were two variables that provided a non-random amount of variance: The vehicle length and the ground_clearance. Both of these have extremely small p-value meaning that they had a high level of significance. The coefficients and 

2: Is the slope of the linear model considered to be zero? Why or why not?

The slope of the linear model is not considered to be zero. This is because the linear regression shows that some of the independent variables had a significant effect on the dependent variable. If none of the independent variables had an effect on the dependent variable then the linear regression would result in a near zero slope.

3: Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

The main indicator of whether the linear model predicts the mpg of the MechaCar is the r-squared value. that shows there is more than 70 percent chance that this model would approximately predict the mpg of the MechaCar correctly . In my opinion, the model would be considered effective.

## Deliverable 2: Summary Statistics on Suspension Coils
1: The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

#### Lot Summary Table 

![Lot Summary PSI](https://user-images.githubusercontent.com/93050682/155803302-6d896f4b-7fc7-44a2-83cc-45ba8bbda26c.PNG)

#### Total Summary Table 

![Summary PSI](https://user-images.githubusercontent.com/93050682/155803540-1af9faa3-4e2b-4404-b209-a3fa0cbfad6c.PNG)

The picture above show that overall the current manufacturing data meets this design specification for all manufacturing lots in total as it less than 100 PSI but when we look at lots individually , lot 3 has PSI way more than acceptable specification that is why , the lot 3 doesnt meet the criteria. 


## Deliverable 3: T-Tests on Suspension Coils

1: Is the PSI across all manufacturing lots is statistically different from the population mean of 1,500 pounds per square inch?
![Summary PSI](https://user-images.githubusercontent.com/93050682/155805191-e9292a11-76fb-4a91-a875-c2982d373dff.PNG)

Loooking at the data, and using .05 significance level , it quite eveident as the p-value is more than significance level, we can not regect the null hypthesis that is the mean of sample is equal to mean of population.

2: Is the PSI for each manufacturing lot is statistically different from the population mean of 1,500 pounds per square inch?

Picture below shows that the p value for lot 1 is equal to 1 and lot 2 is equal to 0.6 way more than outr significance level. Hence the null hypothesis can not be rejected , but in the case of lot 3 , we can reject the null hypthesis stating that the mean of lot 3 is not equal to mean of the population. This analysis indicates that the company needs to look further into its lor 3 and make changes. 
![Lot Mean vs Population](https://user-images.githubusercontent.com/93050682/155805882-6eef4ba2-cdf3-42fc-bd6f-623b52ea5100.PNG)

## Deliverable 4: Study Design: MechaCar vs Competition





