# MontyHall_jupyter

http://mathworld.wolfram.com/MontyHallProblem.html

Often quoted in probability courses. This random simulation in python runs the Monty Hall problem several thousand times 
and records the number of wins/fails when changing which door is picked, vs when sticking with the players original choice. 

Insight to the crux of the problem may be found by examining the code around where the game-show host opens the door (before 
offering the player the choice to switch). The logic here effectively states that the game-show host identifies the door with 
the car and actively opens a different door. In doing so he reveals new information to the contestant, increasing their odds 
of winning a car by switching a door. This is predecated on the fact that their initial choice was probably a goat (66.666% 
likely to be a goat), but if they switch it's only 50% likely to be a goat.

Logging can be enabled which outputs the result from each run of the game. This produces very long output quite quickly though!

## Azure instance
https://notebooks.azure.com/tawfiq-hamid/projects/montyhall-jupyter/html/MontyHall.ipynb

## Further reading:
http://mathworld.wolfram.com/MontyHallProblem.html
https://www.khanacademy.org/math/precalculus/prob-comb/dependent-events-precalc/v/monty-hall-problem
https://en.wikipedia.org/wiki/Monty_Hall_problem
