# Read Me!

## Overview
This repository hosts Jupyter notebooks used to analyze how different fight values in the game MESBG affect the win rate.
This game is mostly determined by dice throws: the person with the higher dice throw wins. In case of a draw, the person with the higher fight value wins. Otherwise, there is a roll-off, where on 1–3 one person wins, and on 4–6 the second person wins.

## Analysis 
The analysis is done by simulating three scenarios:
- fight value is equal to the enemy
- my fight value is higher than the enemy (I win in case of a draw)
- the enemy has a higher fight value (the enemy wins in case of a draw)

For every scenario, a matrix is prepared based on the number of dice that I and the enemy are using.
The matrix is prepared for every possible combination up to 10 dice.
For every combination, 1000 simulations are done.

## Visualisation
Every scenario is presented on a heat map using Matplotlib.
The greener the value is, the higher the probability of winning.



