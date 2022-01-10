# School_District_Analysis

# Purpose:
The purpose of this project was to analyze data from a set of high schools in a given school district and to find patterns in math and reading scores and factors associated with higher and lower scores. Furthermore, a refactoring of the data was required after notification from the school board that there may have been false scores reported from a certain school's 9th grade class. This project afforded me the opportunity to analyze data for patterns as well as to correct my findings once discovering that some data values were required to be discarded. 

# Results:
* How is the district summary affected?

The school district summary was minimally affected by the removal of the Thomas High School 9th Grade data. As evidenced in the images below, the change was significant enough only to make a 0.1-0.2% change in the measurement of "% Passing Reading" and "% Overall Passing."

![](https://github.com/aaronwolfeaaron/School_District_Analysis/blob/main/District_Summary_Old.png)
![](https://github.com/aaronwolfeaaron/School_District_Analysis/blob/main/District_Summary_New.png)

* How is the school summary affected?

The school summary changes are best appreciated when broken down by factor (school size, school type, budget) and those factors will be addressed below. 

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

There was not a dramatic change in Thomas High School's overall performance relative to other schools. In fact, Thomas High School had the second highest overall passing rate of the fifteen schools in the study.

![](https://github.com/aaronwolfeaaron/School_District_Analysis/blob/main/Top_5_Schools.png)

* How does replacing the ninth-grade scores affect the following:

* Math and reading scores by grade: The reading scores improved more than the math scores. The math score was not changed at the tenths place of a percentage. 

* Scores by school spending: Scores by school spending were relatively unchanged. Thomas High School stayed within the previously assigned bin after removing the ninth grade scores. 

* Scores by school size: Thomas High School is quite large so the overall effect on the data was small due to the fact that the average across the school was not much affected by the removal of the ninth grade scores and the power of an outlier was diminished by sheer data amount. 

* Scores by school type: Thomas High School being a charter school did slightly move the data to show favortism towards the charter system in producing higher test scores. 

# Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

Because Thomas High School is a large, well-funded school, there were not overly remarkable changes in the data analysis after removing the ninth grade scores. Below are four key findings.
1. Because Thomas High School is large, the removal of scores did not have an appreciable impact because the outliers within Thomas High School scores did not skew the data of such a large group.
2. Because Thomas High School was already one of the most well-funded schools in the district, the amount of money per student also did not have an appreciable effect because the other grades still performed above average once the ninth graders were removed. Therefore, the Thomas High School scores overall were largely unchanged. 
3. The reading scores for Thomas High School did appreciably increase, but math scores did not, when ninth grade scores were removed. The average school in the district had significantly lower math than reading scores, so this was not a surprising finding. 
4. Despite removal of the ninth grade scores, Thomas High School was the second highest performing overall in the district. This shows that while the ninth grade data were skewing the data, the factors of school size, budget, spending per capita, etc. had mixed well to provide an impactful learning environment for the students. 
