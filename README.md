# Lunar Lander Reinforcement Learning

This project demonstrates a reinforcement learning (RL) agent trained to play the Lunar Lander game using a Deep Q-Network (DQN). The agent learns to navigate and land a spacecraft on the lunar surface in the `LunarLander-v2` environment provided by OpenAI's Gym.

## Features

- **Deep Q-Network (DQN)**: Utilizes a neural network to approximate the Q-value function.
- **Experience Replay**: Stores and samples past experiences to enhance learning stability.
- **Epsilon-Greedy Policy**: Balances exploration and exploitation during training.
- **Video Recording**: Captures and displays the agent’s gameplay.

## Requirements

- Python 3.x
- PyTorch
- Gymnasium
- Additional libraries

You can install the required packages using the following commands:

```bash
pip install gymnasium
pip install "gymnasium[atari, accept-rom-license]"
apt-get install -y swig
pip install gymnasium[box2d]
```

## Usage
1. Run the training script:

2. Execute the following command to start training the DQN agent:

```bash
python train.py
```

3. Training Details:

The agent will be trained over 2000 episodes.
Training progress, including average scores, will be printed to the console.
The trained model will be saved to checkpoint.pth once the environment is solved (average score >= 200.0).
View the Agent’s Gameplay:

After training, the agent’s gameplay video will be saved as video.mp4 and displayed in the notebook.
