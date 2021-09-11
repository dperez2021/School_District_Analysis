# School_District_Analysis

## Purpose of the School District Analysis

The School Board hired a consulting firm to analyze a set of student data because of academic dishonesty that was found regarding Thomas High School 9th graders which seems to be altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help She has asked me to replace the math and reading scores for Thomas High School with NaNs (Not-a-Number) values while keeping the rest of the data intact. Once replaced the math and reading scores should be analyzed and documented with any changes.The Purpose of the School District Analysis is to find the overall passing percentages of the students and see if there is any correlation with the budget per student. In addition we have found is that some of the test scores from the 9th grade at Thomas High School are missing, therefore we remove the tampered data and analyze its effect on the district.

## Development Enviornment
- Jupyter Notebook
- Python 3.7
  - Numpy
  - Pandas

## Deliverable 1

Ninth grade math and reading scores are replaced

![DELIVERABLE 1 REPLACE NINTH GRADE SCORES](https://user-images.githubusercontent.com/88256967/132957424-13004d61-6cc5-47a4-bf31-11d14ba0f97a.PNG)

## Deliverable 2

### District Summary

![DELIVERABLE 2 1 District Summary](https://user-images.githubusercontent.com/88256967/132957444-15a783d3-06c2-450a-a54b-f27cb07497c1.PNG)

### School Summary

![DELIVERABLE 2 2 School Summary](https://user-images.githubusercontent.com/88256967/132957446-29ef13b7-445a-4bf6-9b90-1ef9cd267d7e.PNG)

### Top 5 Performing Schools

![DELIVERABLE 2 3 Top Performing Schools](https://user-images.githubusercontent.com/88256967/132957496-b78b01d7-e9a8-4d67-b08c-04e0ce610c5a.PNG)


### Bottom 5 Performing Schools

![DELIVERABLE 2 4 Bottom Performing Schools](https://user-images.githubusercontent.com/88256967/132957502-c61b156c-3f4b-459f-a8e6-c80ff17542b2.PNG)


### Average math score for each grade level from each school

![DELIVERABLE 2 5 Average Math Scores](https://user-images.githubusercontent.com/88256967/132957519-386b40f4-ef87-442b-b377-8d34b3ef1fb0.PNG)


### Average reading score for each grade level from each school

![DELIVERABLE 2 6 Average Reading Scores](https://user-images.githubusercontent.com/88256967/132957528-b77cf914-5594-4f0d-b855-614e02f1714c.PNG)


### The Scores by School Spending

![DELIVERABLE 2 7 Scores by School Spending Per Student](https://user-images.githubusercontent.com/88256967/132957534-7072605e-1c04-40d8-ab6b-b36ad130c3d9.PNG)


### The Scores by School Size

![DELIVERABLE 2 8 Scores by School Size](https://user-images.githubusercontent.com/88256967/132957537-45dacab3-6df2-4c35-b07e-eb24f4137e40.PNG)


### The Scores by School Type

![DELIVERABLE 2 9 Scores by School Type](https://user-images.githubusercontent.com/88256967/132957551-6c0dba9e-d41d-4160-bfb1-198af6fb111e.PNG)


## Results

### Affect on District Summary

Below is the original district data

![Deliverable 3 1 Before](https://user-images.githubusercontent.com/88256967/132957594-b4ecb67b-20ca-43e6-9859-d384248eb49a.PNG)

After the tampered data from Thomas High School grades are removed the passing percentages across the math and reading are affected by a 1% fall. No effect on the average scores for math and reading.

![Deliverable 3 1 After](https://user-images.githubusercontent.com/88256967/132957598-6719579a-8dae-4d99-a101-d754f55b7270.PNG)


### Affect on School Summary

The affect on the school summaries only had an affect on Thomas High School as the 9th Grade scores of Math and Reading were removed. Once replaced the NaN is displayed throughout those values

![DELIVERABLE 2 5 Average Math Scores](https://user-images.githubusercontent.com/88256967/132957657-2135773f-7222-4939-b78b-bac2058e592f.PNG)
![DELIVERABLE 2 6 Average Reading Scores](https://user-images.githubusercontent.com/88256967/132957660-f3acff02-535e-4109-bc74-fdc82cffd4b8.PNG)

### Affect on Performance of Thomas High School

The affect the replacement of 9th Graders scores by NaN relative to their perofrmance has an affect when compared to other schools as they have no data to compare to which         would reduce the overall performance.

### Data Replacement Results

- Affect on Data replacement (Math & Reading)
  - The data replacement that occured for Thomas High School did not change the reading and math scores by grade. The scores were still satisfied by school and grade level. The       summary tables displayed NaN for ninth grade column and the remaining data remained the same without change.

- Affect on Data replacement (School Spending)
  - The changes did not affect the school spending summary. The only affect replacing the data had was on the spending ranges for passing percentages. 

- Affect on Data replacement (School Size)
  - Based on the school  size there is no difference on the average math and reading scores.

- Affect on Data replacement (School Type)
  - There is no change in the average math and reading scores based on the school type.

## Summary

Reviewing the analysis closely after replacing the Thomas High School 9th Grader scores with Nan resulted in some noticeable changes to the distric:
  - School by School comparison on a grade level of 9th graders would not be able to be done versus Thomas High School
  - The percentage of students who passed both the math and reading exams for the districts was lowered by one tenth of a percentage point.
  - The overall school performance has an effect once you remove the data set of 9th Graders this would be heavily reduced as it can't be discredited it still needs to be calculated with the amount of students in total regardless of the scores that are omitted which brings down the average of performance.

Module 4 - Anaconda - PythonData (Python 3.7)










