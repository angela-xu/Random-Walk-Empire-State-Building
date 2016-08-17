# Random Walk Simulation
## Introduction
In this repository, a classic random walk problem was solved by using Monte Carlo simulation. Visualizations of random walk processes
and results were also provedied.
* The program is written in Python.
* Three files are included: 1) random_walk.py - simulation code; 2) plot_random_walk.png - plots of random walk processes of 1000 simulations;
3) histogram_random_walk.png - histogram of end steps of 1000 simulations.

## Random Walk Problem
You are walking up the Empire State Building and playing a game with your friend. 

For 100 times, you roll a dice:
* If it is 1 or 2, you go one step down.
* If it is 3, 4, or 5, you go one step up.
* If it is 6, you roll the dice again, and walk the resulting number of steps up.
* You can not go below step 0.
* You have a 0.1% chance of falling down the stairs when you make a move - falling down means you have to start again from step 0.

And you bet your friend that you will reach 60 steps high. What is the chance that you will win this bet?

## Visualizations & Results
![plot_random_walk](https://cloud.githubusercontent.com/assets/19921232/17342885/0c18b364-58b0-11e6-855c-4bb08f2506c2.png)

![histogram_random_walk](https://cloud.githubusercontent.com/assets/19921232/17342922/3274106c-58b0-11e6-838e-619d1cfdc452.png)

* Chance that you will win this bet: 72.68%

## Installation and Usages
* Downlaod and run random_walk.py.
* Parameters could be customized.   
