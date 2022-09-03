# School_District_Analysis
Module 4 of Bootcamp, learning panda and Jupyter Notebook

## Overview of the school district analysis: 
The purpose of the school district analysis is to see where the district is at, and see if there are any trends in the data. First, two different csv files are worked with, and eventually some of the data from each file is combined together into a dataframe (table). Average math and reading scores are calculated per school. Then that data is used to calculate the percent of students passing math, reading, and both per school. Finally, these calculations are analyzed to see if there are any trends for what makes a school more successful.

## Results
Replacing the freshmen results from Thomas High School with NaN (basically erasing the data) does not have a huge impact on the data.
This is the district summary before the data was erased:

https://github.com/Betsy-Kalkwarf/School_District_Analysis/blob/main/Resources/Alphabetical%20school%20summary.png

This is the district summary after the data was erased:

https://github.com/Betsy-Kalkwarf/School_District_Analysis/blob/main/Resources/After.png

The school summary for Thomas High School was not hugely impacted, and when listing the Top 5 performing schools before and after erasing the data Thomas High School is second.

Top 5 Before:
https://github.com/Betsy-Kalkwarf/School_District_Analysis/blob/main/Resources/Top.png

Top 5 After:
https://github.com/Betsy-Kalkwarf/School_District_Analysis/blob/main/Resources/Top%20after.png


The math and reading scores per grade did not have data for the 9th graders at Thomas High School after they were replaced with NaNs.
The per student spending data did not change with the erasing. 

https://github.com/Betsy-Kalkwarf/School_District_Analysis/blob/main/Resources/Spending%20per%20student.png

The data based on school size also was not affected by the erasing. 

https://github.com/Betsy-Kalkwarf/School_District_Analysis/blob/main/Resources/School%20Size.png

The data based on type of school also was not affected by the erasing. 

https://github.com/Betsy-Kalkwarf/School_District_Analysis/blob/main/Resources/School%20type.png

## Summary: After the reading and math scores for the ninth grade at Thomas High School were replaced with NaNs there were slight changes in the data. Before the NaNs, Thomas High School had a math average of 83.4, reading average of 83.8, % passing math of 93.3, % passing reading of 97.3, and % overall passing of 90.9. After the NaNs, Thomas High School had a math average of 83.4, reading average of 83.9, % passing math of 93.2, % passing reading of 97.0, and % overall passing of 90.6.
