# DQN on CartPole-v0

This repository contains an implementation of the **Deep Q-Network (DQN)** algorithm applied to the **CartPole-v0** environment using the **Gymnasium (new)** library.

The code is based on the original implementation from [this repository](https://github.com/SeeknnDestroy/DQN-CartPole/blob/master/dql-cartpole.ipynb), with modifications in Gymnasium library.

## Overview

The CartPole-v0 environment is a classic reinforcement learning problem where the objective is to balance a pole on a moving cart. The task involves controlling the cart’s horizontal position to prevent the pole from falling over. The DQN algorithm is used to learn the optimal policy for this task.

### Key Features:
- **Environment**: CartPole-v0 from Gymnasium (new version of OpenAI's Gym)
- **Algorithm**: Deep Q-Network (DQN)
- **Libraries**: 
  - Gymnasium
  - PyTorch
  - Numpy

## Requirements

To run this project, you will need to install the following dependencies:

```bash
pip install gymnasium torch numpy
```

## References
Original Implementation: [DQN-CartPole by SeeknnDestroy](https://github.com/SeeknnDestroy/DQN-CartPole/blob/master/dql-cartpole.ipynb)