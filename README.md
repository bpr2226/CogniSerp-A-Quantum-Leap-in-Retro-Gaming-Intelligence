
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
