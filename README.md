# School District Analysis	
## `-Indice-`	
	
- [Overview of the Project](#overview-of-the-school-district-analysis)	
- [Resources](#resources)	
- [School District Analysis Result](#School-District-Analysis-Result)	
  - [How is the district summary affected](#How-is-the-district-summary-affected)	
  - [How is the school summary affected](#How-is-the-school-summary-affected)	
  - [Thomas High School’s performance relative to the other schools](#performance-relative-to-the-other-schools)
  - [How is replacing the ninth-grade scores affected](#How-does-replacing-the-ninth-grade-scores-affect)		 
- [School District Analysis Summary](#School-District-Analysis-Summary)	
	
## `Overview of the school district analysis`	
	
The purpose for the analysis of 15 school districts was to delivery: 	
1. An overview of the district's key metrics	
2. An overview of the key metrics for each school	
3. Tables presenting each of the following metrics:	
    - Top 5 and bottom 5 performing schools, based on the overall passing rate	
    - The average math score received by students in each grade level at each school	
    - The average reading score received by students in each grade level at each school	
    - School performance based on the budget per student	
    - School performance based on the school size 	
    - School performance based on the type of school.	
	
 Additionally, because of some not accurate data from Thomas High School's 9th grade the analysis was repeated again with changed data NaNs for 9th graders at Thomas High School. So, the impact of changed data is explained in this report.	
## `Resources`	
The analysis was created using next resources:	
  - Data Source:  [Resources](./Resources/)	
  - Software: Python 3.8.8, Anaconda 4.10.3., Jupyter-notebook : 6.3.0.	
## `School District Analysis Result`	
	
Full results can be found in the [City Schools Analysis](./PyCitySchools_Challenge.ipynb) file.	
  ### ` - How is the district summary affected`	
	
The screen below shows that the district summary was affected by changing data of Thomas High School slightly:	
![image](https://user-images.githubusercontent.com/68247343/126917260-9d6f821e-b6db-438f-b69c-9b2adb75fb48.png)	

In other words: district's key metrics were decreased as Average Math Score by 0.1, % Passing Math by 0.2 and % Passing Reading by 0.1%, % Overall Passing by 0.2%.
  ### ` - How is the school summary affected`	

The school summary has increased for Thomas High School with key metrics significantly:
  - % Passing Math more then 26%, 
  - % Passing Reading more then 27%, 
  - % Overall Passing 25%.
  
![image](https://user-images.githubusercontent.com/68247343/126929760-97c2c2d1-a995-4d61-afe8-93548d29ea06.png)

  ### ` - Thomas High School’s performance relative to the other schools`	

Thomas High School’s performance was improved and it puts them for the top 5 schools.

![image](https://user-images.githubusercontent.com/68247343/126929806-02e4869e-5203-4bb9-8333-13a1441f0cc0.png)
 
  ### `- How does replacing the ninth-grade scores affect`	

 - There is no data "Math and reading scores by grade" for Thomas High School’s because it was replaced to NaNs.

![image](https://user-images.githubusercontent.com/68247343/126929963-c31a7449-4800-47de-b2b2-1b2c114ab1ae.png)

 - Scores by school spending was changed slightly for Thomas High School’s bin $630-644.

![image](https://user-images.githubusercontent.com/68247343/127004060-33ecaf82-f1f7-4266-bfa2-af62ab56cb58.png)

 - Scores by school size was changed slightly for the medium size as Thomas High School is.

![image](https://user-images.githubusercontent.com/68247343/127003781-2f9cb8e2-57d8-4a2c-943c-98058907cc36.png)

- Scores by homas High School’s Chapter school type was changed also slightly.

![image](https://user-images.githubusercontent.com/68247343/127003866-dfe9c608-d3f7-432c-94e9-3247cb003610.png)

	
## `School District Analysis Summary`	
	
Four changes to the school district analysis after reading and math scores have been replaced:
  - The district summary was affected by changing data of Thomas High School slightly.
  - The school summary has increased for Thomas High School with key metrics significantly.
  - Thomas High School’s performance was improved and it put them for the top 5 schools.
  - There is no data "Math and reading scores by grade" for Thomas High School’s because it was replaced to NaNs. But, scores by school spending, scores by school size, and scores by school type were changed slightly.
