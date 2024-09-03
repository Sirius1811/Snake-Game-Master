# Snake Game with AI

## Overview
This project implements a classic Snake game using Python and Pygame, enhanced with AI capabilities. The AI is trained using a Deep Q-Network (DQN), a type of reinforcement learning algorithm, allowing it to learn and improve its performance over time. The AI controls the snake, making decisions based on the game's state to maximize its score.

## Features
**Classic Gameplay:** Enjoy the traditional Snake game with a twist.
**AI Integration:** The AI uses reinforcement learning to control the snake's movements.
**Dynamic Learning:** The AI learns and adapts through continuous play, improving its strategy over time.
**Visualization**: Real-time plotting of scores and mean scores during training.

## Installation
To run the game on your local machine, follow these steps:

**Clone this repository:**
git clone https://github.com/Sirius1811/Snake-Game-Master.git
cd snake-game-ai

**Install the required dependencies:**
pip install -r requirements.txt

**Run the game:**
python agent.py

## Usage
**Training the AI:** The AI will automatically start learning once you run the agent.py file. It will continuously play the game, learning from its actions and outcomes.
**Playing the Game Manually:** You can modify the game.py file to allow for manual control if you wish to play the game yourself.

## How It Works
The AI in this project is based on a Deep Q-Network (DQN). Here's a brief overview of how it functions:

**State Representation:** The game state is represented as an array of 11 values, capturing information about the snake's environment (e.g., obstacles, food location).
**Action Space:** The AI can choose from three actions—move straight, turn left, or turn right.
**Reward System:** The AI receives positive rewards for eating food and negative rewards for colliding with walls or itself.
**Training:** The AI uses the Q-learning algorithm to train a neural network that predicts the best action to take given the current state.

## Dependencies
Python 3.7+
Pygame
Numpy
Matplotlib
Torch
All required dependencies can be installed using the requirements.txt file.

## Project Structure
├── game.py          # Core game logic and AI interaction
├── model.py         # Neural network model and training logic
├── agent.py         # AI agent for training and decision making
├── helper.py        # Helper functions for plotting
├── requirements.txt # Required dependencies
└── README.md        # Project documentation

## Contributing
Contributions are welcome! If you have any ideas, feel free to open an issue or submit a pull request.
