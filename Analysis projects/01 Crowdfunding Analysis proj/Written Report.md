# FACTORS OF SUCCESSFUL KICKSTARTER PROJECTS

## Overview of Project

### Purpose
To explore the dataset of KickStarter projects to discover factors that affect the outcomes of those projects.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Here is the outcomes of all KickStarter projects about theaters relating to its launch dates. Based on the chart, we can see that most campaigns maintained a similar successful rate when started on January, February, March, April, August, and September. May, June, and July had the most campaigns launched and the highest successful rates. However, this rate declined towards the end of the year and reached the lowest point on December. The failure rate was maintained consistently in a range of 31 to 52 units, touched the lowest point on November and March, and reached peaked on May, June, July, and October. 

![Theater Outcomes Based on Launch Date](https://github.com/dennisphan/DU-Boot-Camp---Data-Analytics/blob/44a2f4d81875df1918291ecd4dc469a3abb410ac/Analysis%20projects/01%20Crowdfunding%20Analysis%20proj/Resources/03%20Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
Based on the below chart of outcomes based on goal, we can see that the success of Kickstarter campaigns correlated oppositely with the preset goal. In specific, the success rate was highest at the beggining of the year and then declined gradually with the increments of the goal. However, this was completely true. When the goal ranged from $35,000 to less than $45,000, the success rate was unexpectedly high. The failure rate was opposite with the success rate when it started low at lower goals and increased when the goal went up. Coincidentally, the failure rate also dropped down suddently at the range of $35,000 to $45,000. Another thing to notice is that the number of projects with a goal of $15,000 and higher was mostly less than 30, especially at the $40,000 to $45,000 range and $45,000 to $50,000 range which had only 3 and 1 project repsectively. 
![Outcomes Based on Goal](https://github.com/dennisphan/DU-Boot-Camp---Data-Analytics/blob/44a2f4d81875df1918291ecd4dc469a3abb410ac/Analysis%20projects/01%20Crowdfunding%20Analysis%20proj/Resources/04%20Outcomes_vs_Goals.png)

### Analysis of Central Tendency of Goal and Pledged
Based on below data, we can see that successful campaigns had much lower goal than failed projects. The difference between goals of successful and failed projects were quite large, from two to three times.  

![Descriptive Statistics](https://github.com/dennisphan/DU-Boot-Camp---Data-Analytics/blob/154e429d09fdae60969aeaa7dbe2f393445e9204/Analysis%20projects/01%20Crowdfunding%20Analysis%20proj/Resources/06_Descriptive_Statistics.png)

Based on the quartile calculations, we can also see that most values of this dataset stayed at the lower portion but there were some outliers with very high value had driven the mean and median of both sucessful and failed projects. In short, many outliers had driven the distribution of this dataset. 

![Central Tendency of Goal and Pledged](https://github.com/dennisphan/DU-Boot-Camp---Data-Analytics/blob/154e429d09fdae60969aeaa7dbe2f393445e9204/Analysis%20projects/01%20Crowdfunding%20Analysis%20proj/Resources/05_Central_Tendency_of_Goal_and_Pledged.png)

### Challenges and Difficulties Encountered
For some categories, there were not enough projects

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Two conclusions: (1) the best time to launch a KickStarter campaign is May, June, and July to maximize the probability of success. (2) 
- What can you conclude about the Outcomes based on Goals?
Two conclusions: (1) the lower the goal, the higher the chance a KickStarter campaign would succeed, and (2) to have a high goal, the range from $35,000 to $45,000 should be considered. However, this situation might not be reliable since the analyzed data was not large enough. 
- What are some limitations of this dataset?
This dataset has some limitations. Firstly, it includes mostly projects in the U.S (3038 projects out of 4015 in total) and in the UK (604 projects out of 4015 in total). The results could reflect only situations in the U.S and the UK. Secondly, there are a lot of outliers with values that are far outside of the IQR. This indicates that the result is heavily influenced by those outliers to be less reliable. Thirdly, in the analysis of Outcomes Based on Goal, the number of projects with goal ranging $15,000 and higher are not large enough. This could make the trend discovered from the analysis less valuable. 
- What are some other possible tables and/or graphs that we could create?
