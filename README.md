# Deep-Reinforcement-Learning-with-Atari

Hey everyone!
Here I will be showing all my code for my project on creating an Agent to play atari games.










If you want a more in depth break down of the code and reasoning behind it check out my [article](https://mark-youngson5.medium.com/so-you-want-to-play-atari-games-e9252762a142) I wrote on it!

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [What is Deep RL?](#What-is-Deep-RL?)

## General info
This project was inspired by the research paper [Human Level Control Through Deep Reinforcement Learning](https://drive.google.com/viewerng/viewer?url=https://web.stanford.edu/class/psych209/Readings/MnihEtAlHassibis15NatureControlDeepRL.pdf) written by Google DeepMind in 2015
	
	
	
## Technologies
Project is created with:
* Python version: 3.6.7
* Pytorch version: 1.0.0
* numpy: 1.16.4



## What is Deep RL?
Before we get into any of the details, let me first explain what is going on.

The goal of an RL problem is to create a agent that maximizes some reward in an environment. In this case we are trying to get the agent to maximize the amount of points it can get in Pong(Atari Games). The environment is the game that the agent is playing, and to receive rewards it has to take an action. There are many different algorithmns that can get the agent to maximize its long term reward. A very common example would be Q learning. In this example after every action the agent takes in its environment, it receives a reward and a new state, and it stores all this information in what is called a Q table. After thousands of iterations the agent will have mapped out all the possible actions, and in turn all of the rewards. The agent then can take the action that gives the agent the greates reward. 

Deep Reinforcment learning is the combination of using neural networks to predict the value of each action the agent can take in a given state. So in pong the options would be moving the paddle to the right, to the left, 
