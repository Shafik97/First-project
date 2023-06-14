# First-project
  This is my first project of building a dashboard in excel using a fictional data obtained from Kaggle. The scenario is if I were a Math teacher how should I analyse the data of previous exam and come with a solution to improve the score on the upcoming exam?

  First, I cleaned the data as there were many blank spaces. I wanted to fill the blanks randomly from the items that are already in that column. So, I made a list of items that are in the column and using this formula, =INDEX(Array,RANDBETWEEN(1,ROWS(Array)),1) to get a random value from the list. I searched for blanks using Special Find, then I copy and pasted the formula using ctrl+enter. Then, I set it as a table and inserted a pivot table in another worksheet. 

  Next, I grouped the data of Math Scores in the pivot table into 4 grades which are Failed (0-39), C (40-59), B (60-79), A(80-100). Here, I encountered a challenge when I cannot group them into 4 groups at once because the data is too big and it crashed my excel. So, I have to do a workaround by grouping them one at a time, then make a new pivot table and add another group. After I finished grouping, I think this data is ready to be analyzed.

  I thought parents have a significant effect towards students' studies, so I started with comparing the education and marital status of parents of students in grade A and Failed. To my surprise they did not have a large influence in their children's results. As seen in Graph1 and Graph2 below, Marital Status of parents in both groups are identical as Married holds the largest number, then single, divorced, and widowed. However, when comparing the number of degree holders parents in both groups, Group A have a higher percentage compared to group Failed. But, this did not have a big influence on the scores as there are also non-degree holders parents in Group A. And the number of degree holders parents children in group Failed is quite large which is 21.3%. So, I explored other factors as well.

<image src="https://github.com/Shafik97/First-project/assets/136435447/fdd6c978-2519-4bf2-8736-6482879944b3" width="270" height="250">
<image src="https://github.com/Shafik97/First-project/assets/136435447/e80e7ef8-d465-4b6b-88c1-1c0c9275359a" width="270" height="250">

  I compared both groups Weekly Study Hours, Test Prep and Lunch Type. But, the most stark difference was Lunch Type. There is a higher percentage of 87.58% of students in Group A who ate standard lunch compared to 25.62% in group Failed. However, Weekly Study Hours comparison showed little difference as both groups have high number of people who studied more than 10 hours and less than 5 hours. Then, the number of students who have completed Test preparation have some influence also because Group A has higher number of students who completed the Test Preparation compared to group Failed. So, now I have found the main differences between students from group A and who Failed. There are more students in Group A that ate standard lunch, completed test preparation and studied more than 10 hours weekly. 
  
<image src="https://github.com/Shafik97/First-project/assets/136435447/923f01e9-08ff-485c-ba1a-1211d44cb817" width="270" height="250">
<image src="https://github.com/Shafik97/First-project/assets/136435447/c6535764-039e-44c0-ba25-88c067806498" width="270" height="250">
<image src="https://github.com/Shafik97/First-project/assets/136435447/297fd077-22c3-4b7d-960d-e27efc22dda7" width="270" height="250">

  Next, to improve the score on the upcoming exam, I decided to check the weightage of the grades. I found that most students, 48.58% scored Grade B (60-79). So, it is better to focus on this group as they will bring a huge influence. 
