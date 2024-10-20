# Lunar Lander DQN Agent 🚀

## Project overview
This project demonstrates the use of **Reinforcement Learning (RL)**, specifically a **Deep Q-Network (DQN)**, to solve the **Lunar Lander** environment provided by OpenAI Gym. The aim is to train an agent to safely land a spacecraft on the lunar surface between two designated flags. The agent learns to navigate through the environment by optimizing its actions based on rewards, ultimately minimizing fuel consumption and ensuring a soft landing.

## Tools & Technologies
- **Python**: Core language for implementing the RL algorithm.
- **PyTorch**: Deep learning framework for building and training the neural network.
- **OpenAI Gym**: Provides the **LunarLander-v3** environment for agent training and evaluation.
- **Numpy**: For efficient matrix operations and data manipulation.

## Algorithms Used
- **Reinforcement Learning (Q-Learning)**: The agent learns from interactions with the environment by maximizing cumulative rewards.
- **Deep Q-Network (DQN)**: Combines Q-Learning with a deep neural network to handle large state spaces.
- **Experience Replay**: Stores experiences in a buffer and samples them randomly to decorrelate training data.
- **Target Network**: Helps stabilize learning by providing a slower-changing reference for Q-value updates.

## Parameters
- **Learning Rate**: `5e-4`
- **Replay Buffer Size**: `100,000`
- **Minibatch Size**: `100`
- **Discount Factor (gamma)**: `0.99`
- **Epsilon Decay**: Reduces exploration rate as training progresses.

## Training Process
1. The agent interacts with the environment, choosing actions based on the epsilon-greedy policy.
2. Q-values are updated using the DQN algorithm, incorporating feedback from the environment through rewards.
3. Experiences are stored in a replay buffer and sampled for training.
4. The target network is updated periodically to stabilize learning.
5. The agent continues to improve until it consistently lands the spacecraft within the designated area.


## Here is a form of visual removal of results such as video
https://github.com/user-attachments/assets/6624f637-f40c-4f99-987c-c5aa01c6212f



