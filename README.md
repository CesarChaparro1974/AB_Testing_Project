![Alt Text](assets/AB_Testing.png)

# Project description

## Overview
* I am an analyst at a big online store. Together with the marketing department, I've compiled a list of hypotheses that may help boost revenue. 
  I prioritized these hypotheses, launched an A/B test, and analyzed the results. 


### Description of the data
/datasets/hypotheses_us.csv
1. Hypotheses — brief descriptions of the hypotheses
2. Reach — user reach, on a scale of one to ten
3. Impact — impact on users, on a scale of one to ten
4. Confidence — confidence in the hypothesis, on a scale of one to ten
5. Effort — the resources required to test a hypothesis, on a scale of one to ten.
The higher the Effort value, the more resource-intensive the test.

/datasets/orders_us.csv
1. transactionId — order identifier
2. visitorId — identifier of the user who placed the order
3. date — of the order
4. revenue — from the order
5. group — the A/B test group that the user belongs to

/datasets/visits_us.csv
1. date — date
2. group — A/B test group
3. visits — the number of visits on the date specified in the A/B test group specified


### Part 1. Prioritizing Hypotheses
The file hypotheses_us.csv contains nine hypotheses on boosting an online store's revenue with Reach, Impact, Confidence, and Effort specified for each.
#### Task:
- Applyed the ICE framework to prioritize hypotheses. Sorted them in descending order of priority.
- Applyed the RICE framework to prioritize hypotheses. Sorted them in descending order of priority.
- Showed how the prioritization of hypotheses changes when I use RICE instead of ICE. Provided an explanation for the changes.
  
### Part 2. A/B Test Analysis
#### Task:
- Graph cumulative revenue by group. Made conclusions and conjectures.
- Graph cumulative average order size by group. Made conclusions and conjectures.
- Graph the relative difference in cumulative average order size for group B compared with group A. Made conclusions and conjectures.
- Calculated each group's conversion rate as the ratio of orders to the number of visits for each day. Ploted the daily conversion rates of the two groups and described the difference. Drawed conclusions and made conjectures.
- Ploted a scatter chart of the number of orders per user. Made conclusions and conjectures.
- Calculated the 95th and 99th percentiles for the number of orders per user. Defined the point at which a data point becomes an anomaly.
- Ploted a scatter chart of order prices. Made conclusions and conjectures.
- Calculated the 95th and 99th percentiles of order prices. Defined the point at which a data point becomes an anomaly.
- Found the statistical significance of the difference in conversion between the groups using the raw data. Made conclusions and conjectures.
- Found the statistical significance of the difference in average order size between the groups using the raw data. Made conclusions and conjectures.
- Found the statistical significance of the difference in conversion between the groups using the filtered data. Made conclusions and conjectures.
- Found the statistical significance of the difference in average order size between the groups using the filtered data. Made conclusions and conjectures.
- Made a decision based on the test results.
