# Navigation Project - Banana RL - Udacity

This project is a submission for the Navigation project with the Udacity Deep Reinforcement Learning Nanodegree.

![bananas](bananas.gif)

In this project I use Deep Q-Learning(DQN) to train an agent to collect bananas within a large 3d world. The project environment is provided by Udacity and is similar but not exactly the same as [Banana Collector](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#banana-collector) environment on the Unity ML-Agents GitHub page. 

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. The goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The environment has a state space of 37 dimensions including basic information about the agent and the "ray-based" perception of the objects it can see.

The task is episodic, and the environment is considered solved when the agent receives an average score of +13 over 100 consecutive episodes. 


The agent has four discrete actions to choose from:
* 0 - Forward
* 1 - Backward
* 2 - Left
* 3 - Right

### Getting started

In order to run this project you will need Python 3.6. 

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
- Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
- Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
- Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
- Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
  (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

  (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

2. Place the file in the repository folder, and unzip (or decompress) the file.

3. Open the Navigation.ipynb notebook and follow instructions there.

### Dependencies

For more information on the project dependencies please have a look at the Udacity repository [dependencies section](https://github.com/udacity/deep-reinforcement-learning#dependencies).
