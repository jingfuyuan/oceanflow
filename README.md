# Ocean flow simulation and Gaussian process  

## Introduction  
This is a project of my MITx course **Data Analysis: Statistical Modeling and Computation in Applications**. This is a very challenging but rewarding project. It is also computationally demanding. I'm pround that I have completed this project and learned a lot from it.

The background of this project is that a plance crashed in the Philippine Archipelago ocean region. The plane debris may be carried away by ocean flows and landed on the coast of some islands. The ocean flow data were observed for some days. The task is to predict the unobserved ocean flows, simulate the movement of plance debris, and suggest some coast regions where one should search for plance debris.

## What I did
- visualized ocean flow with Matplotlib
- implemented `OceanFlowSimulator` class. It can simulate the particle movement in the ocean, plot the trajectory of particles, create animation of the simulation
- implemented gaussian process regression function from scratch
- did grid search for the optimal parameters of the kernel function
- studied how parameters affect the performance of gaussian process model
- compared my gaussian process regression function with `sklearn` gaussian process regressor
- predicted the unobserved ocean flow using gaussian process regression
- simulated the movement of plane debris and found possible coast regions for debris search
- simulated the movement of large number of randomly picked particles and found coast regions where monitoring stations can be set up to monitor general ocean debris