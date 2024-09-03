# CartPole Reinforcement Learning Agent

## Project Overview
This project implements a Deep Q-Network (DQN) agent to solve the CartPole-v1 environment from OpenAI Gym. The agent learns to balance a pole on a moving cart, demonstrating fundamental concepts of reinforcement learning.

## Features
- Implementation of a Deep Q-Network (DQN) agent
- Use of experience replay for improved learning stability
- Epsilon-greedy exploration strategy
- Target network for more stable Q-value updates

## Requirements
- Python 3.7+
- TensorFlow 2.x
- OpenAI Gym
- NumPy

## Project Structure
- `CartPole.py`: Main script containing the DQN implementation and training loop
- `README.md`: This file

## How It Works
1. The DQN agent interacts with the CartPole environment, learning to balance the pole.
2. The agent uses a neural network to approximate Q-values for each action.
3. Experience replay is used to store and sample past experiences for training.
4. An epsilon-greedy strategy balances exploration and exploitation.
5. A separate target network is used to stabilize training.

## Results
After training, the agent should be able to balance the pole for the maximum number of steps (500) consistently. The script outputs the training progress and final test performance.
