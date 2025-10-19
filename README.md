# CS370-ML-ReinforcementLearning
This project implements a Reinforcement Learning (RL) agent that learns to navigate a custom Treasure Maze environment using a Deep Q-Learning approach. The agent explores, learns from experience, and optimizes its path to reach the treasure efficiently.

## Overview

Built with Python, TensorFlow/Keras, and Jupyter Notebook

Implements Q-learning with experience replay and an epsilon-greedy strategy

Features a custom environment (TreasureMaze.py) and memory system (GameExperience.py)

Demonstrates RL concepts like exploration vs. exploitation, reward feedback, and policy optimization

## How It Works

The maze environment is reset with a random start position.

The agent takes actions (up, down, left, right) using exploration or exploitation.

Rewards guide learning—positive for treasure, negative for invalid or repeated moves.

Experience replay improves training stability and performance over time.

The model converges once the agent consistently wins.

## Skills Demonstrated

Reinforcement Learning fundamentals

Neural network–based Q-value estimation

Python and TensorFlow model training

Experience replay and reward optimization
