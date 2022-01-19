# Dining-Philosophers
Implemented a solution of the famous Dining Philosophers problem and one of its modified version. It deals with concurrency and synchronisation issues which are dealt with using mutex as well as counting semaphores

## Problem Statement

Q1) The traditional dining philosopher problem: each philosopher needs the ``` 2 forks  to their left and right ``` to eat their meal. <br>
Q2) This version was modified: the table had 4 sauce bowls in the centre accesible to all the philosophers and 5 forks in the table as is usually done in this problem. The philosopher would need ``` 1 fork ``` and ``` 1 sauce bowl ``` to eat their meal. Note that in this part there is no deadlock. <br>
Q3) This version was modified: the table had 4 bowls in the centre accesible to all the philosophers and 5 forks in the table as is usually done in this problem. The philosopher would need ``` 2 forks to their left and right ``` and ``` 1 sauce bowl ``` to eat their meal <br>

## Steps to run the code

1) Keep all files in the same directory.
2) Run the ``` make ``` command in the terminal.
3) Open the terminal and run either ``` ./dp ``` or ``` ./dp3 ``` according to your need
4) Run ``` make clean ``` to delete the output files and clean up.

## More details on the solution can be found [here] (https://github.com/abhik-s-basu/Dining-Philosophers/blob/main/bonus_WRITEUP.pdf)








