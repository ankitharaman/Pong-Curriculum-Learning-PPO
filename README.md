# Pong-Curriculum-Learning-PPO
Curriculum Learning and Proximal Policy Optimization Approach to Pong

Authors: Alekha Rao and Ankitha Raman
Date: 04/30/25

Overview:
---------
Our final project trains an agent to play a simplified version of Pong using
a combination of Curriculum Learning (through a 5-stage plan) and Proximal
Policy Optimization (PPO), an algorithm that directly optimizes the policy
with its clipped surrogate objective function. We compared our agent's 
performance using 3 plots, each graphed at each stage of the Curriculum
Learning, to an agent solely trained with the PPO algorithm. 

The program outputs 6 figures into respective png files.

Instructions:
-------------

Imports Needed:
- numpy
- matplotlib
- gym
- stablebaselines3
- math


All Source Code is in a jupyter notebook final_project.ipynb that can be run 
cell by cell in order to reproduce our results.
