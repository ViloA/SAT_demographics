# Project 1: SAT & ACT Analysis Overview

### Problem Statement 

Does living in a certain region of the country affect the overall SAT participation rate and test scores?

### Summary

I have been given the task of making recommendations to the mayor of a town in order to improve education outcome for high school students. I chose to use 4 datasets on SAT scores and participation nationwide. The datasets were cleaned and merged together for ease of analysis. After cleaning, exploratory data analysis was conducted in order to look for patterns or insights. After discovering some trends in the data, visualization plots were created so I could more easily demonstrate these trends to an audience with the mayor. A presentation will be conducted with my findings and recommendations at the mayor's earliest convenience. 

### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*object*|SAT|the US state under consideration| 
|**participation_2017**|*float64*|SAT|Mean SAT participation rate in 2017| 
|**ebrw_2017**|*int64*|SAT|Evidence based reading and writing scaled score between 200-800 in 2017| 
|**math_2017**|*int64*|SAT|Math based scaled score between 200-800 in 2017| 
|**total_2017**|*int64*|SAT|sum of evidence based reading and writing + math scores in 2017| 
|**participation_2018**|*float64*|SAT|Mean SAT participation rate in 2018| 
|**ebrw_2018**|*int64*|SAT|Evidence based reading and writing scaled score between 200-800 in 2018| 
|**math_2018**|*int64*|SAT|Math based scaled score between 200-800 in 2018| 
|**total_2018**|*int64*|SAT|sum of evidence based reading and writing + math scores in 2018|
|**participation_2019**|*float64*|SAT|Mean SAT participation rate in 2019| 
|**ebrw_2019**|*int64*|SAT|Evidence based reading and writing scaled score between 200-800 in 2019| 
|**math_2019**|*int64*|SAT|Math based scaled score between 200-800 in 2019| 
|**total_2019**|*int64*|SAT|sum of evidence based reading and writing + math scores in 2019|
|**participation_2020**|*float64*|SAT|Mean SAT participation rate in 2020| 
|**ebrw_2020**|*int64*|SAT|Evidence based reading and writing scaled score between 200-800 in 2020| 
|**math_2020**|*int64*|SAT|Math based scaled score between 200-800 in 2020| 
|**total_2020**|*int64*|SAT|sum of evidence based reading and writing + math scores in 2020| 




### Conclusions and Recommendations

 Given the vague task of "...move the needle on high school education outcomes", I have found that living in a certain region of the United States can have a direct effect on overall SAT scores and rate of participation. It seems in regions that have the greatest participation rate also have the lowest overall SAT scores. We can presume that the schools within states that have made SAT tests mandatory also see overall lower scores. This could be due to the fact that the students might not have been as driven or prepared as effectively as states where the students volunteered to take the tests. This can be seen clearly in the Midwest region across all 4 years where they have the least percentage of participation but the greatest overall scores. The opposite is true with the Northeast region where we see the greatest participation along with the lowest scores in the nation. 

 One other thing worth noting. The Southeast and Southwest regions had quite similar levels of participation but in all 4 years the Southeast region clearly had overall higher scores than the Southwest. More analysis and outside research is required in order to investigate the correlation. 

#### My recommendation to the mayor of the town is as follows:  
- If you would like to see the greatest overall scores of SAT tests, do not make the test mandatory across schools
- Use available resources to assist students who voluntarily wish to take the tests so that they may be better prepared and achieve a greater overall score, thus improving their chances of getting into the college of their choosing.
