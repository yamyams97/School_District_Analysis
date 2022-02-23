# School District Analysis

## Overview 
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

## Results 
Because the school board believed in a possible academic dishonesty case, we found it best to see how the overall scores were affected by the 9th grade class. With that being said, the entire ninth grade class of Thomas High School have had their scores replaced with NaN in our dataframe. 

Relpacing the 9th graders math and reading scores with NaN resulted in:
* The overall passing percentage for Thomas High School fell to 65%
* The overall passing percentage for the entire district fell to 64.9%
* Thomas High School was no longer included on the list of top five schools.
* The overall passing percentages of Thomas High School decreased by 0.11%
* The average scores of Thomas High School for math and reading increased by 0.06
* For the spending range of $630-644 per student, the overall passing percentage decreased by 0.1%
* School rankings are unchanged. Thomas High School is still the second best performing school in the district with an overall passing rate of 90.63% among their tenth through twelfth graders.

## Charter vs. District Schools
Charter schools generally performed better than District schools in this analysis. The top five schools with the highest overall passing percentages are all Charter schools, whereas the bottom five are all District Schools. Charter schools in this dataset were typically characterized as "Small" and "Medium" size schools. According to our dataframe, Charter schools had a 36% higher overall passing percentage than District schools. 

## Effects of School Budget
It is found that Average Scores and Passing Percentages do not increase as spending per student increases. In fact, the top performing school in the entire school district (Cabera High School) received $68 less per student than the lowest performing school (Johnson High School). This implies that there are more relevant factors than funding that decide average student scores.

## Effects of School Size 
When considering School Sizes, "Large" Schools (Over 2,000 Students) have the lowest average scores and passing percentages. The difference in performance between "Small" and "Medium" Size Schools is negligible (approximately 1%). Interestingly, all District schools in this dataset are characterized as "Large" schools. This may be an indication that students in this district learn and perform better in smaller, more intimate settings.
