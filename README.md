# School_District_Analysis
Click here to view the file: [PyCitySchools_Challenge](https://github.com/robbe-verhofste/Py_Schools/blob/main/PyCitySchools_Challenge.ipynb)

## Analysis Overview
In this analysis, a school district approached our team to analyze inconsistencies in 9th grade scores, with concerns over falsified reporting. The school district was also interested in overall metrics comparing grades to total school budget, total students per school, to average math and reading scores, to the passing percent for reading and math, and the overall passing percentage.

As part of this analysis, we replaced inaccurate data for the 9th graders at Thomas High School and kept the remaining data intact.

### Results: Using bulleted lists and images of DataFrames as support, address the following questions.

#### How is the district summary affected?
  *The district summary is minimally affected, with math averages going from 78.98% to 78.93% and reading averages going from 81.87% to 81.85%.
#### How is the school summary affected?
  *The average for Thomas High School decreases slightly
#### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
*It goes down slightly
#### How does replacing the ninth-grade scores affect the following:

The bottom and top 5 schools stayed the same regardless of the inclusion of the falsified scores. Thomas High School also remained the top performing school, with a decrease in total score from 93.3% to 93.2%, a very insignificant reduction.


## Results
Nearly all of the score metrics stated the same after the analysis. Those metrics that did change changed in only miniscule amounts.

###Scores without Thomas Highschool's 9th grade:
![File name](https://github.com/robbe-verhofste/Py_Schools/blob/main/Resources/top5_grade.PNG)

###Scores with Thomas Highschool's 9th grade:
![File name](https://github.com/robbe-verhofste/Py_Schools/blob/main/Resources/top5_w_9th_grade.PNG)
