# A3C for Kung Fu

This project implements an Asynchronous Advantage Actor-Critic (A3C) agent to play the Kung Fu Master game using the OpenAI Gymnasium environment.

## Gymnasium

Gymnasium is a toolkit for developing and comparing reinforcement learning algorithms. It provides a wide range of environments for training agents, including classic Atari games like Kung Fu Master.

## Asynchronous Advantage Actor-Critic (A3C)

A3C is a deep reinforcement learning algorithm that combines the actor-critic approach with asynchronous training. It uses multiple agents, each with its own copy of the environment, to explore different parts of the state space simultaneously. This allows for more efficient learning compared to traditional methods.

## Project Structure

- **agent.py**: Contains the implementation of the A3C agent.
- **network.py**: Defines the neural network architecture.
- **train.py**: Trains the A3C agent using the Kung Fu Master environment.
- **utils.py**: Provides utility functions for video rendering and visualization.

## Requirements

- Python 3.x
- Gymnasium
- PyTorch
- NumPy
- OpenAI Gym

## Usage

1. Install the required packages: `pip install -r requirements.txt`
2. Run `python train.py` to train the A3C agent.
3. Run `python test.py` to test the trained agent.
4. Use `show_video()` function in `utils.py` to visualize the agent's performance.

## Results

The agent successfully learns to play the Kung Fu Master game, achieving high scores after training for a certain number of episodes.

## References

- [Asynchronous Methods for Deep Reinforcement Learning](https://arxiv.org/abs/1602.01783)
- [OpenAI Gym Documentation](https://gym.openai.com/docs/)
