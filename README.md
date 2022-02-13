# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

A linear regression analysis of the miles per gallon of different mechacar prototypes was completed. The variables tracked were vehicle length, weight, the spoiler angle, ground clearance, all-wheel drive. Here is the result summary of the linear regression model:
<img src = "https://github.com/AaronAKTX/MechaCar_Statistical_Analysis/blob/main/resources/MechaCar_MPG_Summary.PNG">

Looking at these results, vehicle length and ground clearance appear to affect the miles per gallon to a statistically significant degree.

### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
- vehicle length
- ground clearance 
### Is the slope of the linear model considered to be zero? Why or why not?
The slope of the linear model is not considered to be zero. A zero would indicate that the was no relation between the variables and the miles per gallon. The p-value of this model is 5.35e-11 which is a very small chance that these variables are not significant.
### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
I think it does a pretty good job of predicting mpg of MechaCar prototypes. The R-squared value is .7149 which means that around 70% of the variation in miles per gallon between different prototypes can be explained by or predicted by the model.

## Summary Statistics on Suspension Coils

###The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not
Here are pictures of the total summary and lot summary dataframes:
<img src = "https://github.com/AaronAKTX/MechaCar_Statistical_Analysis/blob/main/resources/total_summary.PNG">
<img src = "https://github.com/AaronAKTX/MechaCar_Statistical_Analysis/blob/main/resources/lot_summary.PNG">

From the dataframes above it's easy to see that the total variance in psi across all lots  is less than 63 pounds per square inch. Therefore, the desing specification is met for all lots. However, looking at the individual lots, Lot 3 has a variance of over 170 pounds per square inch. This specific lot does not meet the design specifications.

## T-Tests on Suspension Coils

Comparing the population mean against the mean of the sample we have yields the following results.
The mean of the psi in the three lots we have in our sample is 1498.78.

### A Tableau Story of the significant data points can be found here [Link to Story](https://public.tableau.com/app/profile/aaron.hall4277/viz/NYC_Citibike_Challenge_16439586683850/NYCCitiBikeBreakdown)

### Results of Analysis:
- Time per ride:
<img src = "https://github.com/AaronAKTX/MechaCar_Statistical_Analysis/blob/main/resources/MechaCar_MPG_Summary.PNG">

This shows that vast majority of the rides taken are than one hour.  People are usually just going for a quick ride to get from point A to point B.


- Gender Checkout Times
<img src = "https://github.com/AaronAKTX/bikesharing/blob/main/resources/gender_checkout_times.PNG">

The Majority of Citibike riders are male. The average trip duration is consistent between males and females.

- When are people riding?
<img src = "https://github.com/AaronAKTX/bikesharing/blob/main/resources/Times_people_ride.PNG">

People tend to ride most in the morning and in the evening.

- What days are people riding?
<img src = "https://github.com/AaronAKTX/bikesharing/blob/main/resources/Day_and_time_people_ride.PNG">

The busiest day of the week is Thursday.

- Is there a gender difference between when people ride?
<img src = "https://github.com/AaronAKTX/bikesharing/blob/main/resources/Day_time_by_gender.PNG">

Male and female riders have the same day/time riding habits.

- What is the most common day to ride a Citibike?
<img src = "https://github.com/AaronAKTX/bikesharing/blob/main/resources/most_common_day.PNG">

More evidence that Thursday is the busiest day.

### Citibike Summary
In general we learned that there really isn't much of a gender discrepancy around days and time day people like to ride CitiBikes. The majority of the riders are male and the most common trip is 20 minutes or less. To further investigate we could which areas are the most common starting places of bikes rides. We could also see if those popular starting spots were consistent with regard to when people are riding from those spots. This would help ensure we had enough bikes in the right locations at the right times.
