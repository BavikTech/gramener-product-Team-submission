# gramener-product-Team-Submission
Code assignment for Gramener-product-Team-submission 

## Installation and upgrades necessasry
  1.Upgrade Python 2.0 to Python 3.0 :- pip install python --upgrade
  2. install pip :- python get-pip.py 
  3. install pandas :- pip install pandas
  4. install numpy :- git clone https://github.com/numpy/numpy.git numpy
  5. install matplot :- python -mpip install matplotlib
  

## Question 1 - Given two lists L1 = ['a', 'b', 'c'], L2 = ['b', 'd'], find common elements, find elements present in L1 and not in L2?
## Approach :-
Subtract The First list in which you want to find the not common elements from second list(L1-L2)
Code name- List_notcommon.py

## Question 2 - How many Thursdays were there between 1990 - 2000?
## Approach :-
Set the initial date to first day of the year 1990
set the final date to last day of year 2000
Find total number of days in between
Find which date was which day
count the number of thursdays
Code name - numb_of_thursday.py

## Question 3 - var data = [0, 1, 2, 'stop', 2, 0, 1, 'stop'] write a Javascript function or expression that returns an array with justthe zeroes removed.

## Approach :-
Filter the array where 0 is there by creating a function of data!=0 and then filter the array
code name - javascript_return_without_zero.js

## Analytics Use Case 1 - National Achievement Survey
## Question 1 .What influences students performance the most?
## Approach :-
Reading data to dataframe and filling null spaces with 0 for time being
Calculating average score of all the subjects  and converting blank spaces i.e (0 value)to avergae score with respect to that subject.
finding average of all subjects for each student
finding r values i.e regression correlation cofficient value of every factor with each other
plotting the matrix 
magnify to the factor to which you want to see the r values
code name - nation_achievement_survey_question1.py

## Question 2. How do boys and girls perform across states?
## Approach :- 
Reading data to dataframe and filling null spaces with 0 for time being
Calculating average score of all the subjects  and converting blank spaces i.e (0 value)to avergae score with respect to that subject.
finding performance of all the boys  in each subject by finding the average score of boys in each subject for each state and then plotting it normalized manner from minimum 0 to maximum 1.
finding performance of all the girls in each subject by finding the average score of girls in each subject for each state and then plotting it in a normalized manner from minimum 0 to maximum 1.

code name- national_achievement_survey_question2.py

## Question 3. Do students from South Indian states really excel at Math and Science?
## Approach :- 
Reading data to dataframe and filling null spaces with 0 for time being
Calculating average score of all the subjects  and converting blank spaces i.e (0 value)to avergae score with respect to that subject.
finding performance of all the students in math and science by finding the average score of students in each subject for each state and then plotting it in a normalized manner from minimum 0 to maximum 1.
Filtering out the performance of only the south states from all the states
Finding the quartiles with q1<q2<q3<Q4 with q1 having lowest 25% scoring states and q4 with maximun 25% scoring states
plotting the number of south states according to quartiles.

code name - nation_achievement_survey_question1.py

## Result is shown in result folder using images and a document containing the results ,download the code and run it to see yourself





