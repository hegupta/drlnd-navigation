# Deep Reinforcement Learning - Navigation

## Project Overview
The environment for this project is a square world filled with yellow and blue bananas. The goal of the agent is to collect yellow bananas while avoiding blue bananas. The environment thus gives the agent a reward of +1 whenever a yellow banana is collected, and -1 for a blue banana.

The state space is continuous and has 37 dimensions, which include the agent's velocity and some representation of the objects in front of the agent. The action space is discrete and has 4 possible values: forward, backward, left and right.

The environment is considered solved when the agent gets an average reward of at least +13 over 100 consecutive episodes.

## Getting Started
The following are the dependencies for this project:
  
  * Python 3.6 (installed using MiniConda in my case).
  * OpenAI gym (https://github.com/openai/gym) with the classic control (https://github.com/openai/gym#classic-control) and box2d (https://github.com/openai/gym#box2d) environments installed.
  * The python packages listed at https://github.com/udacity/deep-reinforcement-learning/blob/master/python/requirements.txt (can be installed using pip).
  * The project Unity environment. In my case, I used the Linux environment available at https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip. The zip file needs to be copied into the same folder as Submission.ipynb and unzipped there.
  
## Instructions
All the code for the project is inside the Submission.ipynb notebook. Stepping through the notebook should be sufficient to train the agent from scratch and reproduce my results. The only thing which might need to be changed (depending on the reviewer's environment) is the file path with which the Unity environment is initialized (the 6th code cell in the notebook).
