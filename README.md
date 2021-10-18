# School_District_Analysis


## Overview

Take in infomraotn from multiple sources to provide analysis, reporting, and  presentation materials regarding standardized test data. The information is presented to the chief data scientist for a local schoo district.  This report provides insights about performance trends and patterns so the school board and superintentent can make informed, strategic decisions reagrding budgets and priorities at both the school and district levels. 

The data prepared in this report 
Task is to preparing all standardized test data for analysis, reporting, and presentation to provide insights about performance trends and patterns.  Insights are used to inform discussions and strategic decisions at the school and distrcit level.  

Aggregate data and show trends in school performance

At all stages of this project, the detailed data was treated confidentially to protect the students in accordance with the Family Educational Rights and Privacy Act (FERPA). Any information in the final analysis that identifies individual students, must also be considered to be both confidential and sensitive.   

### Adjusted Data
Based upon preliminary report findings, the school board suspected academic dishonesty with the reading and math scores for the ninth graders at Thomas High School. These scores have been removed from the analysis for this final report. 

## Resources
Data Sources: schools_complete.csv; students_complete.csv
Software: Python 3.7, Jupyter 6.3.0, Panda 1.2.4

## Results
In order to remove the 9th Grade Scores from Thomas High School without skewing the results, those scores were all chagned to NaN (not a number). All calculcuations were updated to elimiante these scores from the aggragate data. 

![THS 9th grade scores NaN](https://user-images.githubusercontent.com/90162669/137651818-8d0e53ba-d4ab-455a-9e2e-39d07b01bf9b.png)

- How is the district summary affected?
The impact of removing these students from the overall data was negligible. For exampple, overall distict percentage changed by only XXX % as demonostrated onteh two chargts below. 

- How is the school summary affected and how does it affect Thomas Hight School's performance relative to the other schools?
The impact of the change is much more noticable at the school level. Thomas High School was the second ranked school in the district prior to the adjustment but fell to fourth place afterwords. 

Top five Schools prior to adjustment:
![BA Top 5 Schools](https://user-images.githubusercontent.com/90162669/137653219-775445a5-e9c5-49c2-859e-bb4a9c83299f.png)

Top five schools after the adjustment
![AA Top 5 schools](https://user-images.githubusercontent.com/90162669/137653477-74ae1906-b416-40c8-bf0b-6ec57afd4f41.png)

- How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade
- Scores by school spending
- Scores by school size
- Scores by school type

### Impact of Removing Data
include images of code

### Scores by School Spending
include df image

Before Adjustment


After Adjustment

![AA Spending Bins](https://user-images.githubusercontent.com/90162669/137656607-3088f989-55e6-46dd-92f5-ddbaf3d681a4.png)



### Scores by School Size
include df image   Passing math % went done one percentage point, for medium size schools no other impact. 

Before Adjustment
![BA School Size Chart](https://user-images.githubusercontent.com/90162669/137656512-557cc9ee-f5de-4f44-a38e-957ba33556c2.png)


After Adjustment
![AA School Size](https://user-images.githubusercontent.com/90162669/137656501-d30cfb0e-acb7-47a6-8ac9-e83bdc870882.png)


### Scores by School Type
include df image

Before Adjustment
![BA Type Chart](https://user-images.githubusercontent.com/90162669/137656567-b2818470-e0d4-410c-b061-39012c0da8ca.png)


After Adjustment




## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
add subheading 

All information is available the shared development enviroment and is available on Git Hub.

