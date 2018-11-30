# Udacity Deep Reinforcment Learning Nanodegree - Project 1 - Banana Navigation  

This github repository contains a possible solution for the first project of the Udacity Deep Reinforcement Learning Nanodegree program. It is based on a Unity environment and requires the students to use a DQN ([Deep Q-Network](https://deepmind.com/research/dqn/)) approach to solve the challenge.

You can find the detailed information on the exercise [here](https://github.com/udacity/deep-reinforcement-learning/tree/master/p1_navigation).

Please see the following video to get an overview of the setting. Keep in mind that as part of the exercise one agent is trained, while the demo shows multiple agents.
[Unity ML-Agents Environment - Banana Collectors](https://youtu.be/heVMs3t9qSk)


## The task

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

- '0' - move forward.
- '1' - move backward.
- '2' - turn left.
- '3' - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.


## Prerequisites

In order to run the code in this repository, it is required to follow the instructions as provided in the Udacity Deep Reinforcement Learning Nanodegree repository. To install all required dependencies, please for the instructions provided [ here](https://github.com/udacity/deep-reinforcement-learning#dependencies).


Unity provides a prebuilt simulator for multiple platforms of the banana navigation environment. It is required to be installed and an environment needs to be up and running to train and run the agent in scope of the exercise. Instructions on how to obtain it can be found in the 'Getting started' section in the following [README file](https://github.com/udacity/deep-reinforcement-learning/blob/master/p1_navigation/README.md)


## Instructions
Run the notebook file __navigation.ipynb__ in this repository to further setup the notebook according to your environment, to train the agent, and to run the agent.

The training will generate the file __checkpoint.pth__ with the learned model weights. You can use this to simulate how your trained agent is behaving in the Unity environment.

## Result
Please see the following video that demonstrates the behavior of the agent trained with the DQN. Please note that that a time.sleep(0.1) was introduced into the code before recording the video after each action taken by the agent. Running the agent in the simulator without it might be too fast to follow, depending on the performance of your system.

[YouTube video](https://youtu.be/-76sHFhuDrU)
