# Reinforcement Learning
## Introduction
Reinforcement Learning (RL) is a branch of machine learning that deals with how an agent can learn to make decisions in a dynamic environment, by interacting with it and receiving feedback in the form of rewards or punishments. There are two main types of RL algorithms: Tabular RL and Approximate RL.

## Tabular RL

Tabular RL is a type of RL algorithm that works by constructing a table of values that represent the expected rewards of taking different actions in different states of the environment. The agent uses this table to make decisions based on the highest expected reward.

### The k-armed bandit

The k-armed bandit is a simple example of a Tabular RL problem, where an agent has to choose between k different actions (or arms) to maximize its reward. The agent starts with no knowledge of the rewards associated with each action, and it has to learn by trial and error which action to take.

### Action-value methods

Action-value methods are a family of Tabular RL algorithms that estimate the value of each action in each state by updating the Q-value of that action using the Bellman equation. The most popular action-value method is the Q-learning algorithm.


### Making a Q-table

To implement a Tabular RL algorithm, the agent needs to construct a Q-table that stores the expected rewards of each action in each state. The Q-table is initialized with random values, and it is updated after each interaction with the environment.

## Approximate RL

Approximate RL is a type of RL algorithm that works by approximating the value function using a function approximator, such as a neural network. The agent uses this function to make decisions based on the highest expected reward.

### Function approximation

Function approximation is the process of approximating the value function using a function approximator, such as a neural network. The function approximator takes the state of the environment as input and outputs the expected reward of each action.

### Deep RL

Deep RL is a type of Approximate RL that uses deep neural networks as function approximators. Deep RL algorithms have achieved impressive results in complex tasks, such as playing video games or controlling robots. The most popular Deep RL algorithm is the Deep Q-Network (DQN) algorithm.

In summary, RL algorithms are a powerful tool for learning to make decisions in dynamic environments. Tabular RL works by constructing a table of expected rewards, while Approximate RL works by approximating the value function using a function approximator, such as a neural network.

## Data Resource
Iris Dataser is used to apply the simple Q-learning algorithm.
