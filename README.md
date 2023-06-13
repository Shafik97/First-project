# First-project
This is my first project of building a dashboard in excel using a fictional data obtained from Kaggle. It is about the relationship between Parents' Marital Status and Education and Children's Score in Exam

First, I cleaned the data as there were many blank spaces. I wanted to fill the blanks randomly from the items that are in that column. So, I made a list of items that are in the column and using this formula, =INDEX(Array,RANDBETWEEN(1,ROWS(Array)),1) to get a random value from the list. I searched for blanks using Special Find, then I copy and pasted the formula using ctrl+enter. Then, I set it as a table and inserted a pivot table in another worksheet. 

Next, to find the relationship of Parents Marital Status and Education and Children's Score in Exam, I made a pivot table consist of 
