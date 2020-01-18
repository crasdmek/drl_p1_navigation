# drl_p1_navigation
Deep Reinforcement Learning Nanodegree (Project 1 - Navigation)

# Files included in this project with description:

1. checkpoint.pth - trained model weights
2. dqn_agent.py - python file that includes the dqn agent
3. model.py - the neural network used by the dqn agent
4. README.md - this introductory file
5. Report.odt - final report in odt format
6. Report.pdf - final report in pdf format
7. Navigation-Solution.ipynb - jupyter python file containing navigation solution for this project


# Project Overview

For this project, you will train an agent to navigate (and collect bananas!) in a large, square world.

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

    0 - move forward.
    1 - move backward.
    2 - turn left.
    3 - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.



# Dependencies

Unity ML-Agents https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md

NumPy http://www.numpy.org/

Open AI Gym https://github.com/openai/gym

PyTorch https://pytorch.org/get-started/locally/



# Instructions

All of the code is provided in the Navigation-Solution.ipynb along with documentation and step by step how to run the code (training and testing).



# Ideas for Future Work

The current agent has good robust performance, allowing the agent to train longer has shown the ability to surpass an average score of 15 over 100 episodes but was not necessary for this project.
