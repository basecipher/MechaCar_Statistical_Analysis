# MechaCar_Statistical_Analysis

## Background
A few weeks after starting his new role, Jeremy is approached by upper management about a special project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

## Required Deliverables:
* Deliverable 1: Linear Regression to Predict MPG
![link to story](https://github.com/basecipher/MechaCar_Statistical_Analysis/blob/main/Images/The%20summary%20Linear%20Regression.PNG)

* Deliverable 2: Summary Statistics on Suspension Coils
![Total Summary](https://github.com/basecipher/MechaCar_Statistical_Analysis/blob/main/Images/Summary%20-%20total.PNG)
![Lot Summary](https://github.com/basecipher/MechaCar_Statistical_Analysis/blob/main/Images/Summary%20-%20lot.PNG)

* Deliverable 3: T-Test on Suspension Coils
![Lot 1](https://github.com/basecipher/MechaCar_Statistical_Analysis/blob/main/Images/t_test%20-%20lot%201.PNG)
![Lot 2](https://github.com/basecipher/MechaCar_Statistical_Analysis/blob/main/Images/t_test%20-%20lot%202.PNG)
![Lot 3](https://github.com/basecipher/MechaCar_Statistical_Analysis/blob/main/Images/t_test%20-%20lot%203.PNG)

## Results
Observing the P value for the various manufacturing lots together are all greater than 0.05 and is not significant so metric known as the null hypothesis can be accepted.  Likewise, the null hypothesis for lot 3 and lot 1 can, in addition, be accepted as the P values are also greater that 0.05. Null hypothesis for lot 2 can can be inferenced to be rejected as the P value is less than 0.05.

* Deliverable 4: Design a Study Comparing the MechaCar to the Competition

## Study Design: MechaCar vs Competition
For the purpose of improving current analysis and fair the MechaCar design against the competion, I suppose an analysis on the vehicles fuel efficiency can be juxtaposed.  When we research fuel efficiency, we are better able to extrapolate a very valuable objective:  determining customer's decision making.

1. What metric or metrics are you going to test?

Vehicular fuel efficiency determination is gathered by how far the vehicle can travel per unit of fuel consumed. Therefore, MPG, also known as "miles per gallon" will be the metric used when it comes to testing hypothesis.

2. What is the null hypothesis or alternative hypothesis?

The null hypothesis essentially states the fuel efficiency of all vehicles of the same class will remain under the same constant, while the alternative hypothesis is that the fuel efficiency of all vehicles of the same class will more than likely differ.

3. What statistical test would you use to test the hypothesis? And why?

To peform the test needed to satisfy the hypothesis, an ANOVA test would be ideal. ANOVA tests are useful in this instance because they allow the determination whether there is a statistically significant differenciating factor amongst mean fuel efficiency and the competition's mean fuel efficiency. With this conclusion a tatistical testing is preferred over a t-test because multiple values are being calculated and performing multiple t-tests would allow for a greater margin of error.

4. What data is needed to run the statistical test?

A sample dataset necessary to perform the needed statistical test would be of between 45 through 55, depending on the variance ultimately chosen, of vehicles within the same class followed by their respective fuel efficiency’s calculated in miles per gallon.
