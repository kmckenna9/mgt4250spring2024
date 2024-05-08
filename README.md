# MGT4250 Spring 2024 Course Project
Author: Kailey McKenna, kmckenna9@elon.edu
## Project Description
This repository is for the course project of MGT 4250 at Elon University. The purpose of this project was to provide questions and analytical insights to data of our choosing. I chose to look into the MLB franchise and specifically into the Boston Red Sox.
### Questions of interest
- Question 1 : What ballpark location in the MLB East division has had the largest amounts of total home wins? 
- Question 2 :  How does game attendance affect the Red Sox’s success on the field?
- Question 3: Is there a relationship between walks scored and homeruns scored within Eastern division teams?
### Importance
- This is *especially* **important** because...
 1. Reason: Marketing efforts can be increased geographically through billboards and radio shows as well as coupons in local grocery stores once analysts know what locations are bringing in the most and least number of fans.
 2. Reason: Having this information about how attendance affects team success, marketers can focus on increasing their efforts for big games to increase the odds of winning.
 3. Reason: Seeing how walks correlates to homeruns can help mlb teams and coaches increase their odds of winning with a different approach to the game.
 4. References :
    a. https://www.qualtrics.com/blog/fan-experience/
    b. https://www.qualtrics.com/experience-management/brand/geographic-segmentation/#:~:text=Marketers%20often%20use%20geographic%20segmentation,to%20expand%20into%20new%20territories
## Data Description
Instructions:
1. How to download data
-https://www.openintro.org/data/index.php?data=mlb_teams
-Scroll to bottom of page, select download csv file
2. Data types used : String, Number, and Date data 
### Data used in First Visualization
- Sum Wins - number
- Division ID – string 
- Sum Home attendence – number 
- Ball Park – string 
### Data used in Second Visualization
- Avg Wins – number
- Year - date
- Team name - string
- Avg Home attendence - number
- Avg Homeruns - number
### Data used in Third Visualization
- Year - date
- Team name - string
- Sum Homeruns - number
- Division ID – string
- Sum Walks - number
## My Tableau Workbook
https://public.tableau.com/views/Repository-KM/Dashboard1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link
## Interpreting Visualizations
## Visualization 1
![Sheet 1](https://github.com/kmckenna9/mgt4250spring2024/assets/169082902/6116656d-ee16-4424-b048-599374f2e316)
My first visualization compared Eastern division ballparks and their sum of home attendance compared to their sum of wins. There was a clear correlation between the sum of wins and sum of home attendance therefore indicating a relationship between the two. Fenway Park had the highest home attendance and sum of wins in the eastern division. I colored the sum of wins with a sequential color map to show the descending pattern of the eastern division teams as their sum of home attendence decended accordingly. A large takeaway from this visualization is that there is a strong correlation between eastern division teams sum of wins compared to their sum home attendence, therefore answering Question 1 and partially answering Question 2. 
## Visualization 2
![Sheet 2](https://github.com/kmckenna9/mgt4250spring2024/assets/169082902/01854c98-4c5b-4c0c-9826-3d388436f03f)
My second visualization is a series of three seperate line charts filtered specifically to the Boston Red Sox in attempt to expand my findings from the first visualization. I wanted to specifically look at how their average home attendence compared to average amounts of wins and homeruns over the past twenty years (2000-2020). Because measures like homeruns and wins are largely attributed to team succces, I thouguht it would be intersting to compare these lines to their average hoem attendence after the correlation we found in ther first visualization. As we can see, the lines all follow a very similar path, almost mirroring eachother at points.Knowing this information, I will be able to compare the years of the highest averages to which years the Red Sox had the highest home attendance to see how game attendance affects the Red Sox’s success, and moving forward how the franchise can capitalize on that financially.  
## Visualization 3
![Sheet 3](https://github.com/kmckenna9/mgt4250spring2024/assets/169082902/cf0d8666-58c0-4d97-8265-0652433315f2)
My third visualization looks at the eastern division specifically over the last 10 years. I wanted to see how the Red Sox compared to the other eastern division teams based on their sum of walks and sum of homeruns from 2010-2020. I found there to be a strong positive correlation between the sum of walks and homeruns teams in this division were scoring indicating a relationship between the two. Given this information, we can begin to draw conclusions for example how scoring more walks in a game can lead to scoring more homeruns. Going forward, the Red Sox can take this into account when planning thei game strategy. Knowing the team gains confidence to hit homeruns as a result of scoring walks, they can aim to increase their number of walks scored each game. Scoring more homeruns will lead to the teams higher odds of success coupled with the insights from the first two visualizations. 
## Discussion & Summary
![image](https://github.com/kmckenna9/mgt4250spring2024/assets/169082902/f1c2029c-b4fe-4999-8454-4fb5d870be9a)
