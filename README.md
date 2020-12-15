# Hyperparameter-Optimization-for-Deep-Q-Networks
Final Project for COMS 6998 Deep Learning Systems Performance at Columbia University <br>

Collaborator: **Ananth Ravi Kumar** (https://www.github.com/arkwave) <br>

References: https://github.com/sweetice/Deep-reinforcement-learning-with-pytorch (modified DQN files from this repo)

# To-Do
1) Freeze different sets of hyperparameters when using successive halving to figure out the most significant ones. <br>
2) Use hyperband to search for hyperparameters. <br>
3) Clean up notebooks into more uniform code that can be run efficiently. <br>
4) Add a requirements.txt to shorten code & have cleaner output.

## Projection Description
To measure the sensitivity of Deep Q-Networks on different tasks subject to learning rate, batch size, optimizer, target Q network update step size, discount factor, and other hyperparameters to identify the relationship between hyperparameters and efficient convergence to the optimal policy across different state/action regimes. <br>

## Methods Implemented
Random Search <br>
Successive Halving <br>
Bayesian Optimization

## Implementation Details
View report for in-depth details about our implementation.

## File Descriptions
For successive halving & random search there are two notebooks are each. One is the implementation and the other is visualization of the agent (will soon combine these into one notebook). The reason I separated them was because during visualization, colab would sometimes crash and I didn't want to re-run everything above that. 
