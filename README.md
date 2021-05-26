# UsingSemaphores

![UsingSemaphores](https://user-images.githubusercontent.com/43594702/119715275-a9ab4b00-be18-11eb-9de4-f025f5a11bdc.png)

[See it in action!](https://www.youtube.com/watch?v=qHeY9KjuQok)

## Overview 

This project simulates 2 seesaw riders named Fred and Wilma who take turns pushing up and down on a seesaw. Semaphores are used to insure that only 1 person pushes up at a time, allowing the riders to take turns. The output of the program contains the height that each person is at for each simulation run,  where 1 simulation is represented by a specific person going up and returning back down, or vice versa. The program is configured to perform 10 simulations.

## Assumptions

1.) Fred goes first all the time. He starts at position 1. Wilma pushes up after Fred, she starts at
position 7.

2.) 1 seesaw simulation is represented by a specific person going up and then down or going down and then
up. For this project, I chose to focus on when Fred goes up and down and down and up to count the number of
simulations that have occurred.

3.) Fred and Wilma only use the seesaw for 10 simulations: from the previous line, this means the
simulation ends after Fred has gone either up and down or down and up 10 times.

## How to run 

1.) Compile with: make all 

2.) Run with: make run 

3.) To remove compiled code files: make realclean
