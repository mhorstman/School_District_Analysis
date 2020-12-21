# School District Analysis for PyCity Schools

## Project Overview
The PyCity school board requested an analysis of math and reading scores for the district and a summary by school, shool spedning, school size and school type. After the inital analysis was completed evidence was uncovered that showed academic dishonesty for the Thomas High School (THS) 9th grade math and reading scores. Those scores were removed for the analysis below, however the chnages from the initial analysis are discussed for each metric shown in the results. 

## Resoruces
**Input**: schools_complete.csv, students_complete.csv 
**Software**: Python 3.7.9, Jupyter Notebooks

## Analysis Summary
The analysis shows that increased spending per student does not lead to higher scores but instead the data suggests that it actaully lowers test scores. Additional analysis is needed to determine why increased spending would lead to lower scores. The analysis also shows that larger schools have lower test scores as well as district schools.
The removal of THS 9th grade scores had minimal impact on the analysis, but should be added back in once the new test data is available to get a complete picture of test scores for the district. 

- The Jupyter Notebook with the full analysis is located on GitHub at the following link: [PyCity Challenge](https://github.com/mhorstman/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb)

## Analysis Results
The following show the results of the PyCity schools. The tables show the data without THS 9th grade scores included, but below each table there are bullets on what changed by removing those scores. 

### 1. District and School Summary
#### District Summary
The following shows the overall scores and passing percentages for the PyCity school district. This data is broken out further below. 
![District Summary](https://github.com/mhorstman/School_District_Analysis/blob/main/Analysis/District_Summary.png)

**Change by Removing THS 9th Grade**: 
 - District math score was reduced by 0.1 and there was no change to the district reading scores
 - Changes to the district math, reading and overall passing percentages were minimal and too small to show on the analysis

#### School Summary
The following table shows the scores and passing percentages for each of the schools on the PyCity schools district. There are clear differences between schools and the remaining analysis shows different grouping of the data to show what might be causing the variation. The top 5 schools in the district are
![School Summary](https://github.com/mhorstman/School_District_Analysis/blob/main/Analysis/School_Summary.png)

The top and bottom 5 schools in the district are:
 - Top Schools: Cabrera HS, Thomas HS, Griffin HS, Wilson HS and Pena HS
 - Bottom Schools: Rodriguez HS, Figueroa HS, Huang HS, Hernandez HS and Johnson HS

**Change by Removing THS 9th Grade**:
 - The change to math and reading scores for THS were less than 0.1.
 - THS  math, reading and overall passing scores were reduced by 0.1%, 0.3% and 0.3%, respectively.
 - Removing the 9th grade reading scores did not change THS from being the second highest ranked school in the district.

### 2. Scores by Grade
The following shows the math and reading scores by grade for each school in the district. 
#### Math Scores
![Math Scores by Grade](https://github.com/mhorstman/School_District_Analysis/blob/main/Analysis/Math_Scores_by_Grade.png)

**Change by Removing THS 9th Grade**: 
 - The only change to this table by removing the THS 9th grade scores is "nan" listed for THS which shows that there no values were included in this analysis. 

#### Reeading Scores
![Reading Scores by Grade](https://github.com/mhorstman/School_District_Analysis/blob/main/Analysis/Reading_Scores_by_Grade.png)

**Change by Removing THS 9th Grade**: 
 - The only change to this table by removing the THS 9th grade scores is "nan" listed for THS which shows that there no values were included in this analysis. 

### 3. Scores by School Spending, Size and Type
#### Scores by School Spending
The analysis shows that as spending per student increases the test scores and passing percentages go down. From this analysis it is not clear why increased spending would result in lower scores so additional analysis is needed to determine the reason behind the drop. 
![Scores by School Spending](https://github.com/mhorstman/School_District_Analysis/blob/main/Analysis/Scores_by_School_Spending.png)

**Change by Removing THS 9th Grade**: 
 - There was no apprecable change in the scores by school spending due to the removal of THS 9th grade scores. 

#### Scores by School Size
The analysis shows that small and medium schools have similar scores, however there is a large drop in scores for large schools. Additional analysis is needed to determine the casue of this drop in scores for large schools. 
![Scores by School Size](https://github.com/mhorstman/School_District_Analysis/blob/main/Analysis/Scores_by_School_Size.png)

**Change by Removing THS 9th Grade**: 
 - There was no apprecable change in the scores by school size due to the removal of THS 9th grade scores. 

#### Scores by School Type
The analysis shows that charter shools have much better math and reading scores and passing percentages than the district schools. Additional analysis is needed to determine the casue of this drop in scores for district schools. 
![Scores by School Type](https://github.com/mhorstman/School_District_Analysis/blob/main/Analysis/Scores_by_School_Type.png)

**Change by Removing THS 9th Grade**: 
 - There was no apprecable change in the scores by school type due to the removal of THS 9th grade scores. 
