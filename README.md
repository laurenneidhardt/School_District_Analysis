# School_District_Analysis
Module 4: Pandas and Jupyter Notebooks
## 1. Overview of the school district analysis: Explain the purpose of this analysis.
The purpose of this analysis is to provide metrics about individual schools and the overall disticts. The data pertains to reading and writing overall scoring, and then the overall passing rates. Budget per student relative to passing rates is used to evaluate overall school performance. Due to issues in reporting, Thomas High School 9th grade scores have been removed from the overall evaluation. 
## 2. Results: Using bulleted lists and images of DataFrames as support, address the following questions.

###  * How is the district summary affected? 
   The district summary overall passing percentage drops only about half a percentage point with the NaN values in the data:
   ![GitHub Logo](/images/logo.png)
   But is not greatly affected in the end, as the averages for passing scores is relatively the same once the NaN values are factored out.

###  * How is the school summary affected?  
   When the THS 9th grade scores are dropped to NaN, the school summary is affected by a large drop in THS overall passing percentage, making it a bottom 5 school in the district. Once the NaN values are removed (the 9th grade students), THS resumes its place in the top 5
###  * How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? 
  Once the NaN values are removed from the analysis, the change in percentages passing math, reading and overall is miniscule, no more that 2 100th's of a percent difference, so no major difference.
###  * How does replacing the ninth-grade scores affect the following:
    ** Math and reading scores by grade: When the 9th grade scores are removed, no discernable difference once you only include the 10th-12th grade scores.
    ** Scores by school spending :  When the 9th grade scores are removed, no discernable difference once you only include the 10th-12th grade scores.
    ** Scores by school size:  When the 9th grade scores are removed, no discernable difference once you only include the 10th-12th grade scores.
    ** Scores by school type:  When the 9th grade scores are removed, no discernable difference once you only include the 10th-12th grade scores.
## 3.Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
* All of the averages are significantly lower for THS with the NaN values in the data.
* THS follows the pattern of having a low passing percentage and a higher budget per student. 
* The overall passing percentage drops significantly since THS is a high perfomrning school.
* THS becomes a bottom five school.

