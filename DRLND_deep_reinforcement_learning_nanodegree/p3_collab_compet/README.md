# Project 3: Collaboration and Competition

## Introduction

For this project, the Unity [Tennis](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#tennis) environment is used.

![tennis.gif](tennis.gif)

In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1.  If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01.  Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation.  Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping. 

The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). Specifically,

- After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores.
- This yields a single **score** for each episode.

The environment is considered solved, when the average (over 100 episodes) of those **scores** is at least +0.5.

## Getting Started

### Dependencies

To set up your python environment to run the code in this repository, follow the instructions below.

* Create (and activate) a new environment with python 3.6.

    ```bash
    conda create --name drlnd python=3.6
    source activate drlnd
    ```

* Follow the instructions in [this repository](https://github.com/openai/gym) to perform a minimal install of OpenAI gym.


* Clone the repository (if you haven't already!), and navigate to the [`dependencies/`](../dependencies/) folder in the root of this repo.  Then, install the dependencies.

    ```bash
    git clone https://github.com/kHarshit/udacity-drlnd-projects.git
    cd udacity-drlnd-projects/dependencies
    pip install .
    ```

---

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)

    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux_NoVis.zip) to obtain the "headless" version of the environment.  You will **not** be able to watch the agent without enabling a virtual screen, but you will be able to train the agent.  (_To watch the agent, you should follow the instructions to [enable a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md), and then download the environment for the **Linux** operating system above._)

2. Follow the instructions in [**`Tennis.ipynb`**](https://nbviewer.jupyter.org/github/kHarshit/udacity-nanodegree-projects/blob/master/DRLND_deep_reinforcement_learning_nanodegree/p3_collab_compet/Tennis.ipynb) to train your agent. The trained weights are in `checkpoint_actor_a.pth`, `checkpoint_actor_b.pth`, `checkpoint_critic_a.pth`, and `checkpoint_critic_b.pth`.

3. Check [**`Report.md`**](Report.md) to know more about the learning algorithm and model
   architecture.

