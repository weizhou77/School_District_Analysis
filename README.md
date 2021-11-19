# School_District_Analysis

## Overview of the school district analysis

The purpose of this analysis is to analyze if there is any correlations between the test overall passing percentage and the school budget. During the project, the school board has noticed that there is evidence of academic dishonesty showing that reading and math grades for Thomas High School ninth graders appear to have been altered. This challenge is to replace the reading and math scores for Thomas High School with NaNs while keeping other schools' data. After fixing the data, we will compare the updated data with the original data to see if there is any changes. 


## Results

###  How is the district summary affected?

<img width="957" alt="challenge district summary" src="https://user-images.githubusercontent.com/92563285/142574979-7dac3d9e-bbcc-4f03-963a-e4e53633d48d.png">

<img width="619" alt="Practice district summary" src="https://user-images.githubusercontent.com/92563285/142575002-b145fd93-3b85-4aaa-994a-8569131c2247.png">

We have two district summaries above. The one on the top represents the updated district summary and the bottom represents the original district summary. We can see that the "Total Schools", "Total Students" and "Total Budget" numbers stay the same. In the updated district summary, it drops 0.2% on the Passing Math Percentage, 0.3% on the Passing Reading Percentage and 0.1% on the Overall Passing Percentage. It means that the math and reading scores for the ninth grader in Thomas High School are higher than overall average. 


### How is the school summary affected?


<img width="866" alt="challenge per school summary" src="https://user-images.githubusercontent.com/92563285/142575634-fe86da96-7b0a-440d-9889-523c7a017bb2.png">

<img width="784" alt="practice per school summary" src="https://user-images.githubusercontent.com/92563285/142575666-72fa1915-23f6-45c9-8905-d88534881721.png">

We have two pictures above showing the updated school summary and the original school summary. All the rows on both pictures are the same except the Thomas High School row. On tha updated school summary which is the one on the top shows that it drops 0.1% on the "% Passing Math" column, drops 0.3% on the "% Passing Reading" and 0.3% on the "% Overall Passing" column. It means that the passing percentages for ninth graders in Thomas High School are higher than the passing percentage for the whole Thomas High School.


### How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other school?

<img width="871" alt="Challenge top 5 schools" src="https://user-images.githubusercontent.com/92563285/142576859-e8fdbd67-32b8-4f43-89c3-05e2263b9d8e.png">

<img width="781" alt="practice top 5 schools" src="https://user-images.githubusercontent.com/92563285/142576904-f9bdaa59-c506-4e0e-8a80-306dc77a8fea.png">

The two pictures above reprent the updated top 5 schools which is the one on the top and original top 5 schools. It shows that Thomas High School remain the second out of the top 5 schools. 

### How does replacing the ninth-grade scores affect the following:

#### Math and reading scores by grade:

<img width="309" alt="challenge reading score by grade" src="https://user-images.githubusercontent.com/92563285/142578607-e722e073-47a0-4444-9f39-f8704056bde6.png">

<img width="310" alt="practice reading score by grade" src="https://user-images.githubusercontent.com/92563285/142578640-590ae393-6dad-4468-9c04-68e04c19dc12.png">

<img width="315" alt="challenge math score by grade" src="https://user-images.githubusercontent.com/92563285/142578716-d2da425e-0f7a-472c-b6dd-667e43d1759d.png">

<img width="310" alt="practice math score by grade" src="https://user-images.githubusercontent.com/92563285/142578732-9fa2e29e-f275-4049-9563-086ff9f0cd97.png">

We are comparing the math and reading score by grade after we replace the Thomas High School ninth graders' math and reading score with NaN to the original math and reading score by grade. We can see that every single cell is the same except the two updated data pictures show nan on the Thomas High School ninth grader cell. 

### Scores by school spending

<img width="855" alt="challenge score by school spending" src="https://user-images.githubusercontent.com/92563285/142579140-a24bde50-9bf3-4f7e-8fca-1eeb287d3aef.png">

<img width="784" alt="practice score by school spending" src="https://user-images.githubusercontent.com/92563285/142579155-c1d8ed33-2630-4f38-a59b-a4c19ce0780c.png">

We are comparing the scores by school spending before and after we replace the Thomas High School ninth graders' grade with Nan. We can see that there is no change on both pictures. 

### Scores by school size

<img width="789" alt="challenge score by school size" src="https://user-images.githubusercontent.com/92563285/142579453-557e9798-3734-408a-9e9e-36c596347f10.png">

<img width="765" alt="practice score by school size" src="https://user-images.githubusercontent.com/92563285/142579487-de6391b1-4bcb-4de3-8227-a8a9acb3bbde.png">

We can see from the pictures above that the scores do not change after we replace the Thomas High School ninth graders' grade with NaN.

### Scores by school type

<img width="737" alt="challenge score by school type" src="https://user-images.githubusercontent.com/92563285/142579713-216b4e39-7c3e-4951-862e-29c80d1bdc2f.png">

<img width="721" alt="practice score by school type" src="https://user-images.githubusercontent.com/92563285/142579734-0c9b23c8-8516-4974-8f23-bb137338e114.png">

The scores by school type do not change after we replace the Thomas High School ninth graders' grade with NaN.


## Summary:

After we replace the Thomas High School ninth graders' grade with NaN, the passing percentages for Thomas High School drop a small percent; but the change is not significant. Since we only change a small portion of datas, the change does not affect the school ranking, scores by grade, scores by school spending, scores by school size nor scores by school type. 

















