# First-project
This is my first project of building a dashboard in excel using a fictional data obtained from Kaggle. The scenario is if I were a Math teacher how should I analyse the data of previous exam and come with a solution to improve the score on the upcoming exam?

First, I cleaned the data as there were many blank spaces. I wanted to fill the blanks randomly from the items that are already in that column. So, I made a list of items that are in the column and using this formula, =INDEX(Array,RANDBETWEEN(1,ROWS(Array)),1) to get a random value from the list. I searched for blanks using Special Find, then I copy and pasted the formula using ctrl+enter. Then, I set it as a table and inserted a pivot table in another worksheet. 

Next, I grouped the data of Math Scores in the pivot table into 4 grades which are Failed (0-39), C (40-59), B (60-79), A(80-100). Here, I encountered a challenge when I cannot group them into 4 groups at once because the data is too big and it crashed my excel. So, I have to do a workaround by grouping them one at a time, then make a new pivot table and add another group. After I finished grouping, I think this data is ready to be analyzed.

I think parents have a significant effect towards students' studies, so I started with comparing the education and marital status of parents of students in grade A and Failed. To my surprise they did not have a large influence in their children's results. 

<image src="https://github.com/Shafik97/First-project/assets/136435447/dfb4f706-4543-42a1-81ff-e195083d530f" width="270" height="250">
<image src="https://github.com/Shafik97/First-project/assets/136435447/e80e7ef8-d465-4b6b-88c1-1c0c9275359a" width="270" height="250">
