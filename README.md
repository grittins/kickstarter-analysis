# Kickstarter Analysis with Excel

## Overview of Project
The purpose of this project to create visualization and analyze the Kickstarter campaign outcomes based on their launch dates and their funding goals. 

### Analysis of Parent and Sub-Category Statistics 
A pivot table is created alongside a bar chart for visualization

<img width="1155" alt="Screen Shot 2023-01-15 at 10 50 50 PM" src="https://user-images.githubusercontent.com/104872971/212596004-38cbd739-0f1c-44dd-88ab-b1abfa7138e3.png">

<img width="1158" alt="Screen Shot 2023-01-15 at 11 02 22 PM" src="https://user-images.githubusercontent.com/104872971/212596229-b7a089e5-763e-4804-b0f5-443e06bf6880.png">

### Analysis of Outcomes Based on Launch Date for Theate category
Based on the Launch Date a **pivot table** is created from the Kickstarter dataset to showcase the successful, failed and canceled outcomes in the Theatre Parent category. 

Pivot Table: 

<img width="348" alt="Screen Shot 2023-01-15 at 10 44 51 PM" src="https://user-images.githubusercontent.com/104872971/212594285-ec1db8b9-a79b-476d-9bb1-e88ccfde81e9.png">


A line chart is then created to display the Outcomes based on the launch date. 

<img width="649" alt="image" src="https://user-images.githubusercontent.com/104872971/168637247-a7736d5e-24f0-4db8-a7fa-899278c934e8.png">

### Analysis of Outcomes Based on Goals
A table is created with column names as follows: 
 - Goal	
 - Number Successful	
 - Number Failed	
 - Number Canceled	
 - Total Projects	
 - Percentage Successful	
 - Percentage Failed	
 - Percentage Canceled
  
COUNTIFS formula used to extract the accurate values from the Kickstarter dataset and then the percentages are calculated. A line chart is then created to visualize the percentages of outcomes based on the different levels of goals. 

An snapshot use of COUNTIFS formula:

<img width="828" alt="Screen Shot 2023-01-15 at 10 47 03 PM" src="https://user-images.githubusercontent.com/104872971/212594559-ca4b7439-4e18-46e4-a1da-4154d277fe1b.png">

<img width="802" alt="image" src="https://user-images.githubusercontent.com/104872971/168636838-299d14c3-7279-4b11-bccb-b14a4536756f.png">


## Results

- Conclusions that can be drawn about the Outcomes based on Launch Date

The month of May has the most activities with the most successful outcomes as well. A steady decline in successful outcomes until September when it reached the usual level of successful outcomes and then hitting the lowest on December. 

However, May till August all had roughly the same number of failed campaigns launched.  

- Conclusion about the Outcomes based on Goals

Although the outcomes based on goals is not proportionate we can conclude - as the goal kept increasing it became difficult to get a succesful campaign.

- Limitations of this dataset

There are some live event ongoing for which the results are not out yet. Those were not taken into account in order to complete this analysis. 

- Other possible tables and/or graphs that could be created

1) Numbers successful, failed, canceled based on Goals
2) Outcomes based on Launch date on a quarterly basis
