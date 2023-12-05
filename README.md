
# Classic Snake game using Reinforcement Learning

This is a snake game built with python and pytorch. Here we are making the computer learn on how to play the game using Reinforcement Learning techniques using Linear Q-net Alogrithm.

We defined our model using Pytorch Libraries and have used Pygame for the user interface. Below are the environment dependencies and steps to run the game.

## Running the project

We have used python 3.10 Version to run this game on and latest pytorch environment


First run this command in a virtual environment to install the dependencies

```bash
  pip install -r requirements.txt
```

After setting up the environment, try to play the game by yourself by Running

```bash
  python snake_game_human.py
```

This is an interactive game, we humans have to play this game by ourselves. For the model the computer to play this game you need to run,

```bash
  python agent.py
```

Once you start the game, the algorithm will start playing the game and making the moves. It learns from it's actions and for the right move it takes a reward. This will also post the score of each game vs number of games played in a graph as you can see once you play the game with the agent.
Introduction
Background: 
Snake, a timeless classic from keypad phones, takes on a new dimension in this project. The transition from manual gameplay to RL-driven decision-making marks a significant evolution in gaming technology. 
Project Overview: 
We propose the implementation of a Python-based Snake game, incorporating RL principles. This involves creating a game environment, training a Deep Neural Network (DNN) using PyTorch, and applying the Q-learning algorithm for intelligent decision-making. 

Objectives
1.	Implement a Snake game environment. 
2.	Train a DNN using PyTorch for Reinforcement Learning. 
3.	Utilizing the Q-learning algorithm for intelligent decision-making. 



Differentiation Factors:
Innovative Neural Network
The DNN boasts a unique architecture: 11 input layers, 256 hidden neurons, and 3 output layers. Use of the RELU activation function for the final layer. 
Q-Learning Algorithm
 Tailoring Q-learning to discrete state and action spaces. Iterative update of the Q-value function based on observed rewards and transitions. 
Interactive Gameplay
Utilizing the pygame module for enhanced graphics and user interface. Integrating human and RL agent inputs for a dynamic gaming experience. 
Model Persistence
Significance of saving the trained model within the project directory. Practical implications for future iterations or external use. 
Implementation Plan
Snake Game Environment
Mechanics: Grid size, snake positioning, and food generation. Collision detection and user input gathering. 
Deep Neural Network: 
Step-by-step process of training the DNN. 
Visuals or diagrams for clarity. 
Q-Learning Implementation
Application of Q-learning in the Snake game. 
Pseudo-code or flowcharts for clarity. 
Deliverables
Fully functional Snake game with RL capabilities. 
Trained DNN model. 
Documentation and code for the Q-learning algorithm. 

Conclusion
This project not only revives a classic game but propels it into the future with intelligent decision-making. The unique combination of an innovative neural network, Q-learning algorithm, interactive gameplay, and model persistence sets this project apart in the realm of gaming and AI development.
