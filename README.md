# Introduction
This is a Kaggle lux AI project.
Competitors design agents to perform resource gathering, optimizations and allocate spaces to build city blocks in a 1v1 scenario against other competitors. In addition to optimization, The agents designed by each team must be capable of analyzing their opponents and developing strategies to get the upper hand.

Each day, a team can submit up to 5 bots to the competition. Each submission will play episodes against bots submitted by other competitors that have a similar skill rating on the leaderboard. Our objective is to design efficient bots which outperform the competitors and later perform an analysis on which approach yields the most efficient outcome for different kinds of maps.

The data to be analyzed in this project is the activity of the bot and interaction of the bot with the environment. 

Initially, the approach was pretty simple that is to create a basic agent that competes with the opponent.
Slowly, I  have implemented some new reinforcement learning techniques such as collection of resources nearby, building the city near opponent’s camp such that their workers bot cannot move.

# Data information

california_housing_data*.csv is California housing data from the 1990 US Census; more information is available at: https://developers.google.com/machine-learning/crash-course/california-housing-data-description

mnist_*.csv is a small sample of the MNIST database, which is described at: http://yann.lecun.com/exdb/mnist/

anscombe.json contains a copy of Anscombe's quartet; it was originally described in Anscombe, F. J. (1973). 'Graphs in Statistical Analysis'. American Statistician. 27 (1): 17-21. JSTOR 2682899 and our copy was prepared by the vega_datasets library.
