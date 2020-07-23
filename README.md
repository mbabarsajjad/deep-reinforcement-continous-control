# Continous Control Project for double-jointed robotic arm
Project 2 of Udacity's Deep Reinforcement Learning nanodegree program

## Project Details
In this project, agents are trained to continously control the double-jointed robotic arm. The goal of the agents is to maintain the position at the target location for as many time steps as possible. The aim of the project is to train the agents so that they must get an average score of +30 (over 100 consecutive episodes, and over all agents).

- The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm.  
- Each action is a vector with four numbers, corresponding to torque applicable to two joints.  
- Every entry in the action vector should be a number between -1 and 1.

## Getting Started
Following libraries are required:
Python 3.x , Jupyter Notebook, NumPy, matplotlib, PyTorch, UnityEnvironment

## Instructions
Apart from the main Navigation.ipynb file, there are following two additional files which are used in the project:
- model.py: where a neural network is defined using PyTorch and
- ddpg_agent_main: where Deep Deterministic Policy Gradients (DDPG) algorithm is defined.

