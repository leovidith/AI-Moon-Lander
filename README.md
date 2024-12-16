# Lunar Lander Reinforcement Learning Agent

## Overview:
This project demonstrates a reinforcement learning (RL) agent trained to play the Lunar Lander game using a Deep Q-Network (DQN). The agent learns to navigate and land a spacecraft on the lunar surface in the `LunarLander-v2` environment provided by OpenAI's Gym.

---

## Why Use Reinforcement Learning for Lunar Lander?
Reinforcement Learning (RL) is ideal for complex control tasks like Lunar Lander because:
- It maximizes cumulative rewards by learning through trial-and-error.
- It adapts to dynamic environments requiring multi-step decision-making.
- It enables intelligent control for challenges like navigation and precision landing.

---

## Agile Sprint Features:

### **Sprint 1: Environment Setup and Requirements**
- Install required libraries and dependencies:
  - Gymnasium (for the `LunarLander-v2` environment).
  - PyTorch (for building the DQN model).
- Validate the lunar landing simulation environment.
- **Deliverable**: Configured and validated game environment.

### **Sprint 2: Model Architecture Design**
- Design the DQN with layers suitable for processing game state inputs.
- Implement Experience Replay for efficient learning.
- **Deliverable**: Initial DQN model ready for training.

### **Sprint 3: Training Pipeline Development**
- Implement epsilon-greedy exploration to balance exploration and exploitation.
- Train the agent over 2000 episodes:
  - Monitor average scores and training progress.
  - Save the model checkpoint upon reaching target performance (average score >= 200).
- **Deliverable**: Trained DQN model and training logs.

### **Sprint 4: Gameplay Recording and Evaluation**
- Implement video recording to capture the agent’s gameplay.
- Validate the agent’s performance in solving the environment.
- **Deliverable**: Gameplay video (`video.mp4`) and performance evaluation report.

### **Sprint 5: Deployment and Documentation**
- Deploy the trained model and gameplay viewer on the platform.
- Provide user-friendly documentation:
  - How to train the agent.
  - How to view and analyze gameplay.
- **Deliverable**: Deployed solution with complete user documentation.

---

## Features:
- **Deep Q-Network (DQN)**:
  - Neural network approximation for Q-value function.
  - Decision-making based on maximizing rewards.
- **Experience Replay**:
  - Stores and reuses past experiences to enhance learning.
- **Epsilon-Greedy Policy**:
  - Balances exploration of new actions with exploitation of learned strategies.
- **Gameplay Video Recording**:
  - Captures and displays the agent’s gameplay for analysis and visualization.

---

## Example Usage:

### Training the Agent:
Run the following command to start training:

```bash
python train.py
```

### Gameplay Recording:
After training, the gameplay video will be saved and displayed:

```bash
video.mp4
```

---

This Agile implementation provides a structured pathway for delivering a reinforcement learning agent capable of mastering the Lunar Lander environment with technical rigor and user engagement.

