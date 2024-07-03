# Tictactoe_q_learing_ML
https://colab.research.google.com/github/vishal815/Tictactoe_q_learing_ML/blob/main/tictactoe_q.ipynb

![1_KBrRlD4jlyeOQMI-usMfIw](https://github.com/vishal815/Tictactoe_q_learing_ML/assets/83393190/b7aa8b7c-3de7-46d6-bbbd-d4b2964378d9)



# Tic-Tac-Toe Q-Learning

## Overview

Welcome to the Tic-Tac-Toe Q-Learning project! This repository contains a Python implementation of a Tic-Tac-Toe game using Q-learning, a type of reinforcement learning. The goal is to train an agent to play Tic-Tac-Toe optimally through self-play and learning from its experiences.

## Features

- **Tic-Tac-Toe Environment**: A simple implementation of the Tic-Tac-Toe game.
- **Q-Learning Algorithm**: Train an agent using Q-learning to play Tic-Tac-Toe.
- **Interactive Gameplay**: Play against the trained agent.
- **Visualization**: Visualize the game board and the agent's decisions.

## Colab Notebook

You can also run the project directly in your browser using Google Colab. The Colab notebook contains all the code and explanations.

[Open in Colab](https://colab.research.google.com/github/vishal815/Tictactoe_q_learing_ML/blob/main/tictactoe_q.ipynb)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/vishal815/Tictactoe_q_learing_ML.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Tictactoe_q_learing_ML
    ```
3. Install the required dependencies (if any):
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the main script to start the training process:
    ```bash
    python main.py
    ```
2. After training, you can play a game against the trained agent by running:
    ```bash
    python play_game.py
    ```
3. Follow the prompts to make your moves and see the agent's responses.

## Code Explanation

### Tic-Tac-Toe Environment

The `TicTacToe` class defines the game environment, including the board, player moves, and winning conditions.

1. **Reinforcement Learning**: Q-learning is a reinforcement learning algorithm that involves training an agent to make decisions by interacting with an environment. In the case of Tic-Tac-Toe, the agent learns to make moves on the game board to maximize its chances of winning.

2. **Q-Table**: In Q-learning, a Q-table is used to store the expected rewards for taking various actions in different states of the game. The agent updates this table through iterative learning to make better decisions over time.

3. **States and Actions**: In the context of Tic-Tac-Toe, states represent the current arrangement of Xs and Os on the board, and actions correspond to valid moves the agent can make. The agent chooses actions based on the information in the Q-table.

4. **Rewards**: The agent receives rewards for its actions, with a positive reward for winning the game, a negative reward for losing, and potentially smaller rewards for other outcomes like drawing the game.

5. **Exploration vs. Exploitation**: Q-learning balances exploration (trying new actions to discover their rewards) and exploitation (choosing the best-known actions) to gradually improve its game-playing strategy.


### Playing with Trained Agent


Tic-Tac-Toe Q-Learning is a beginner-friendly example of using reinforcement learning to solve a simple game. It can serve as a stepping stone to understanding more complex problems and reinforcement learning techniques. The end goal is to have an agent that can play Tic-Tac-Toe optimally, making the best moves possible to either win or force a draw in every game.
