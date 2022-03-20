# School_District_Analysis
## Overview of the school district analysis 
The school board has requested data for the school district, including: A summary of metrics for the whole district, metrics for each school, metrics per grade per school, top five schools, bottom five schools, breakdown based on spending, breakdown based on size, and breakdown based on type. The school board found issues with the scores of Thomas High Schools's ninth grade class. These scores have been removed.

## Results 
Using bulleted lists and images of DataFrames as support, address the following questions.
### How is the district summary affected?
Original:
![Original District Analysis](https://raw.githubusercontent.com/kwarzeski/School_District_Analysis/main/Resources/District_Analysis.png)
Adjusted:
![Adjusted District Analysis](https://raw.githubusercontent.com/kwarzeski/School_District_Analysis/main/Resources/Adjusted_District_Analysis.png)
The removal of Thomas High Schools's ninth grade class affected the percentages slightly. The Original Calculation did not include the decimal place, so a rounding error may have occured.
### How is the school summary affected?
Original:
![Original THS Analysis](https://raw.githubusercontent.com/kwarzeski/School_District_Analysis/main/Resources/THS_Analysis.png)
Adjusted:
![Adjusted THS Analysis](https://raw.githubusercontent.com/kwarzeski/School_District_Analysis/main/Resources/Adjusted_THS_Analysis.png)
The removal of Thomas High Schools's ninth grade class affected the percentages of passing grades:
- Passing math lowered less than 1%
- Passing reading lowered less than 1%
- Passing overall raised by 3%
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
The change in Thomas High School's overall passing % pushed them from 2nd highest scoring school to top school.
### How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade - no longer available for Thomas High School Ninth Grade. All other scores unaffected.
  - Scores by school spending are not affected - Thomas High School fell into the 631-645 range
Original:
![Original THS Analysis](https://raw.githubusercontent.com/kwarzeski/School_District_Analysis/main/Resources/Spending_Ranges.png)
Adjusted:
![Adjusted THS Analysis](https://raw.githubusercontent.com/kwarzeski/School_District_Analysis/main/Resources/Adjusted_Spending_Ranges.png)
  - Scores by school size are not affected - Thomas High School fell into the Large school category
Original:
![Original THS Analysis](https://raw.githubusercontent.com/kwarzeski/School_District_Analysis/main/Resources/Size_Ranges.png)
Adjusted:
![Adjusted THS Analysis](https://raw.githubusercontent.com/kwarzeski/School_District_Analysis/main/Resources/Adjusted_Size_Ranges.png)
  - Scores by school type -only the overall passing % was changed, by 1% - Thomas High School fell into the Charter school category
Original:
![Original THS Analysis](https://raw.githubusercontent.com/kwarzeski/School_District_Analysis/main/Resources/Types.png)
Adjusted:
![Adjusted THS Analysis](https://raw.githubusercontent.com/kwarzeski/School_District_Analysis/main/Resources/Adjusted_Types.png)

## Summary
The removal of Thomas High Schools's ninth grade class scores resulted in changes to:
- The top 5 schools list, most significantly, placing Thomas High School as the top school
- The overall passing % for Thomas High School raised by 3%
- The reading and math passing % for Thomas High School both lowered
- The overall passing % for Charter schools raised by 1%
