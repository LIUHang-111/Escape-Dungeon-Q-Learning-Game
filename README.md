# Escape-Dungeon-Q-Learning-Game

## Project Overview

This project implements a reinforcement learning agent using the Q-learning algorithm to solve a grid-based dungeon escape game.  
The agent learns to navigate through the dungeon, avoid traps, and reach the exit by maximizing cumulative rewards.

The environment contains obstacles and special tiles that affect the agent's movement, making the task more challenging.

---

## Algorithm

The agent is trained using the **Q-learning algorithm**, a model-free reinforcement learning method.

The Q-value update rule is:

Q(s,a) = Q(s,a) + α [ r + γ max(Q(s',a')) − Q(s,a) ]

Where:

- **s** : current state  
- **a** : action  
- **r** : reward  
- **γ** : discount factor  
- **α** : learning rate  

The agent gradually learns an optimal policy through repeated interaction with the environment.

---

## Project Structure

Escape-Dungeon-Q-Learning-Game
│
├── assets/                         # Game interface images and visual assets
│
├── escape_dungeon/                 # Game environment and source code
│
├── Escape Dungeon Q-Learning Game.ipynb   # Jupyter notebook demonstration
│
├── training_log.txt                # Training process output log
├── report.pdf                      # Project report
│
├── README.md                       # Project documentation
└── .gitignore

##how to run

1. Download the escape_dungeon folder (or the zipped file) from this repository.

2. The folder contains:
assets/ – game interface images and visual assets
source code for the dungeon environment and Q-learning agent

3. Open the Jupyter Notebook:
   Escape Dungeon Q-Learning Game.ipynb
   
4. Open the Jupyter Notebook.

Note:
The code currently uses hard-coded image paths.
You may need to modify the image loading paths in the code so that they match the location of the assets folder on your computer.
