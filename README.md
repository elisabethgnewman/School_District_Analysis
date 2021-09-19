# School_District_Analysis

## Overview of School District Analysis
The purpose of the School District Analysis was to help a city's school system's board review and analyze their school district's testing proficiency. We utilized Python, Jupyter Notebook, and Anaconda to retrieve, clean, organize, and visualize the data. Throughout Module 4, we pulled in two CSV files: students_complete and schools_complete. With these CSV files, we found missing values, corrected names, retrieved counts, averages, and percentages of the data, and created data frames to present a district analysis. For Module 4's challenge, we were tasked with replacing the 9th grade at Thomas High School's reading and math scores with NaNs because there was a data integrity issue. After replacing these grades, we reperformed the school district analysis.

## Results
After updating the data to replace the Thomas High School 9th graders' reading and math scores with NaNs, we reran the district analysis.

### District Summary and School Summary Changes
The district summary changed because the total number of students decreased from 39,170 to 38,709 because we removed the 461 9th graders from Thomas High School. The school summary also changed because the Thomas High School average scores were adjusted to remove the 9th graders. The average grades for Thomas High School decreased.

![image](https://user-images.githubusercontent.com/88783255/133934584-30b4762b-cd84-4744-b1df-3f22152cab63.png)
**Thomas High School Complete Data**
![image](https://user-images.githubusercontent.com/88783255/133934460-c3b16626-11ea-4c5c-b05e-effc034251eb.png)
**Thomas High School (9th Grade Removed)**
![image](https://user-images.githubusercontent.com/88783255/133934548-04950ba2-9b6d-481a-b63b-8f1855cb52d4.png)

Prior to changing the Thomas High School 9th graders' scores to NaN, Thomas High School was on the top five school list (see screenshot below).
**Top 5 Schools Before Removing Thomas High School 9th Grade Data**
![image](https://user-images.githubusercontent.com/88783255/133936733-3dc537bc-68cf-45ca-a277-d6e5c7107e6f.png)

After removing the scores for the 9th graders at Thomas High School, the school was no longer on the top five list.
**Top 5 Schools After Removing Thomas High School 9th Grade Data**
![image](https://user-images.githubusercontent.com/88783255/133936778-8f4c87fa-5ada-4dbe-a383-8dbe73584f20.png)

## Summary
By removing the Thomas High School 9th graders' scores, their average scores decrease. This makes sense because we were told that there was a data integrity issue with the grades we removed, so they were likely inflating the average.
