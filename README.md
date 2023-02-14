# WumpusWorld
Environment and Various Type of agents for wumpus world
# Wumpus World 

#### -- Project Status: [Active]

## Project Intro/Objective
The purpose of this project is to create the environment and explore various types of agents to solve a classic intelligent Agent game of Wumpus World. 


### Methods Used
* Logical Programming
* Probabilistic Programming
* Reinforcement Learning

### Technologies 
* Python
* jupyter notebooks

## Project Description
The goal of the game is for the agent to climb out of the start cell after finding gold placed in one of the random cells. The agent dies if it walks into a cell with a Wumpus or a bottomless pit and receives a large negative reward.
The game consists of several parts - the environment that needs to generate gold, the creature Wumpus and pits, and keep track of how its state changes depending on the actions of the agents. The environment also generates percepts and rewards for the agent to rely on. The game engine is required to provide all the interactions between the agent and the environment. The agent is not allowed to peek at the state of the environment.
We are exploring various types of intelligent agents, including Naive agent (completely random), Beeline Agent (uses graph search to find optimal path back after grabbing gold) etc. The agents use different kind of intelligence from Logical programming to Reinforcement Learning to maximize the reward. 


## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. The .ipynb file could be opened in Jupiter Notebooks. All required logic is contained directly in this file.


