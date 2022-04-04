# School_District_Analysis

## Overview
This analysis has been conducted to see how different schools within a school district perform based on their students' results in standardized testing in Math and Reading. The results have been gathered using the marks in standardized testing. 

The schools have then been compared based on capita per student (spending per student), school size (small, medium, large) and the type of school (Charter or District). 

Due to potential dishonesty during the standardized testing at *Thomas High School*, the analysis had to be performed a second time around, at which point the test results for grade 9 students at *Thomas High School* have been omitted to create more accurate results.  

## Results

### How is the district summary affected?
Due to potential dishonesty during the standardized testing at *Thomas High School*, the analysis was conducted twice. The second time, the data for all grade 9 students at *Thomas High School* was replaced by **NaN** and omitted from the calculations of the analysis. 

The district results have changed due to omitting the data values. See below the results prior to removing the data for grade 9 students at *Thomas High School*:

![District Data prior to Dishonesty](images/district_results_prior.PNG)

The district results vary after the grade 9 data has been removed. Please see below:

![District Data updated](images/district_results_updated.PNG)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

School Summary prior to NaN Replacement
![District Data School Summary](images/results_per_school.PNG)

School Summary after NaN Replacement
![District Data School Summary](images/results_per_school_updated.PNG)
Replacing the ninth graders' math and reading scores with NaN resulted in the following changes for Thomas High School:

The overall passing percentage for Thomas High School increased to 90.63% from 
The overall passing percentage for the entire district increased to 

When the ninth graders' of Thomas High School had their scores omitted from the calculations, the following changes occured:

The overall passing percentages of Thomas High School decreased by 0.11%
The average scores of Thomas High School for math and reading increased by 0.06
For the spending range of $630-644 per student, the overall passing percentage decreased by 0.1%
School rankings are unchanged. Thomas High School is still the second best performing school in the district with an overall passing rate of 90.63% among their tenth through twelfth graders.

### How does replacing the ninth-grade scores affect the following:
#### Math and reading scores by grade
#### Scores by school spending
#### Scores by school size
#### Scores by school type

## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
