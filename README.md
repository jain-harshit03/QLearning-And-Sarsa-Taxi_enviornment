# Reinforcement Learning in Taxi Environment

This repository contains implementations of Q-Learning and SARSA algorithms applied to the classic taxi environment in reinforcement learning.

## Overview

- `q_learning.py`: Implementation of Q-Learning algorithm, updating Q-values off-policy.
- `sarsa.py`: Implementation of SARSA algorithm, updating Q-values on-policy.
- `taxi_environment.py`: Custom environment setup for the taxi problem.
- `main.py`: Example usage of both algorithms in the taxi environment.

## Usage

1. Clone the repository: git clone https://github.com/your_username/reinforcement-learning-taxi.git


## Q-Learning

- Off-policy RL method updating Q-values by maximizing future rewards.
- Learns optimal policy without following it directly.
- Explores actions using ε-greedy exploration.

## SARSA

- On-policy RL approach updating Q-values based on the current policy's action.
- Learns Q-values while following the policy directly.
- Balances exploration and exploitation using ε-greedy strategy.

## References

- Sutton, R. S., & Barto, A. G. (2018). Reinforcement Learning: An Introduction. MIT Press.
- OpenAI Gym: https://gym.openai.com/
   
