# School_District_Analysis


## Overview

For this project, we are reviewing standardized test data for high school students at a local school district. The analysis and presentation materials in this report will provide insights about performance trends and patterns so the school board and superintendent  can make informed, strategic decisions regarding  budgets and priorities at the district level and for individual  schools. 

At all stages of this project, the detailed data was treated confidentially to protect the students in accordance with the Family Educational Rights and Privacy Act (FERPA). All information in this analysis that identifies individual students must also be considered both confidential and sensitive by readers of this report.   

### Adjusted Data
Based upon preliminary report findings, the school board suspected academic dishonesty with the reading and math scores for the ninth graders at Thomas High School. These scores have been removed from the analysis for this final report. 

## Resources
- Data Sources: schools_complete.csv; students_complete.csv
- Software: Python 3.7, Jupyter 6.3.0, Panda 1.2.4

## Results
The scores for all 9th Graders from Thomas High School were changed to NaN (not a number) to avoid skewing the other results. All calculations were updated to eliminate these scores from the aggregate data. 

![NaN code](https://user-images.githubusercontent.com/90162669/138533827-287dd12e-11ae-4478-802d-00303fc20364.png)

![THS 9th grade scores NaN](https://user-images.githubusercontent.com/90162669/137651818-8d0e53ba-d4ab-455a-9e2e-39d07b01bf9b.png)

## Impact of Removing Data

### District Impact
The impact of removing these students at the district level was negligible. For example, the '% Overall Passing' decreased by only 0.3% as demonstrated  on the two charts below. 

**District Summary Before Adjustment:**
![BA District Summary](https://user-images.githubusercontent.com/90162669/138365206-b02b7b8b-7644-4db5-9d5a-da8207d8bc3c.png)


**District Summary After Adjustment:**

![AA District Summary](https://user-images.githubusercontent.com/90162669/138365232-a9442985-ab35-4849-b831-7e05b1b78ae1.png)


### School Summary Impact
The impact of the change is only slightly more noticeable  at the school level. Thomas High School's '% of Overall Passing' changed by 0.3%.  They were originally the only school in second place;  after the adjustment, they are now tied for second place with two other schools. 

**Top Five Schools Prior to Adjustment:**
![BA Top 5 Schools](https://user-images.githubusercontent.com/90162669/138364802-c966e960-295b-42b6-ad18-66f842ee7be6.png)


**Top Five Schools After the Adjustment:**
![AA Top 5 schools](https://user-images.githubusercontent.com/90162669/138364782-8d7172a3-0837-46d9-9a55-6026d1376880.png)


#### Math and reading scores by grade
The impact of the change was limited to the ninth graders at Thomas High school. 

![math scores before and after](https://user-images.githubusercontent.com/90162669/138534994-6f8875a0-a630-45d3-bcc1-3bb6786f707e.png)


![reading scores before and after](https://user-images.githubusercontent.com/90162669/138535054-2947d81f-3082-42ff-b50d-040d76ccb58e.png)


#### Scores by School Spending


**Before Adjustment:**
![BA Spending Bins](https://user-images.githubusercontent.com/90162669/138526015-cc603467-2671-4c1b-a450-b73c433de43f.png)


**After Adjustment:**
![AA Spending Bins](https://user-images.githubusercontent.com/90162669/138526032-f41711a3-a761-4c11-8730-ac2069234e71.png)


#### Scores by School Size

**Before Adjustment:**
![BA scores by school size](https://user-images.githubusercontent.com/90162669/138526833-4f7bd9b2-a1f8-42ff-8ed7-87957f298e9f.png)


**After Adjustment:**
![AA scores by school size](https://user-images.githubusercontent.com/90162669/138526841-9f5a2184-941c-4a81-a8a9-38ab92c6780b.png)


#### Scores by School Type

**Before Adjustment:**
![BA scores by school type](https://user-images.githubusercontent.com/90162669/138527523-6ac37fdc-1b44-47cf-8844-6bdc844f6f65.png)


**After Adjustment:**
![AA scores by school type](https://user-images.githubusercontent.com/90162669/138527515-a55e0b5c-ff66-4a64-9ff9-b397024be177.png)



## Summary
As demonstrated above, the overall impact of eliminating Thomas High School's ninth grade scores was negligible. A few areas where changes can be seen are: 
- Thomas High School is no longer alone in the second place spot of high performing schools. 
- Math and Reading scores by grade.
- The scores for the $630 - $644 spending bin. 
- The reading and overall percentages for medium size schools

All information is available the shared development environment and is available on Git Hub.

