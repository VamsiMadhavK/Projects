Q-learning algorithm in Grid World
=============

Implements the Q-learning algorithm for an agent to navigate a grid world

Table of Contents
-----------------

-   [Project Title](#project-title)
-   [Description](#description)
-   [Installation](#installation)
-   [Output](#Output)

Description
-----------

This is a Python code that implements the Q-learning algorithm for an agent to navigate a grid world. The grid world has a defined size, obstacles, a terminal state, and a jump that leads to a higher reward. The Q-table is initialized with zeros and updated based on the agent’s actions and the resulting state and rewards. The agent’s exploration rate decreases over time to shift from exploration to exploitation. The code calculates the state visit frequency and probability over all episodes and prints the Q-table and the state-action values. Finally, the agent’s movements on the grid are visualized using a heatmap. This code can be used as a template to apply the Q-learning algorithm to other grid worlds or environments.

Installation
------------
```python
pip install -r requirement.txt 

```

Output
------------

![Optimum Reward](https://out-image/Q-Learning%20Agent%20Final%20Result%20Reward%2011.png)
Fig1. Optimum Reward
![Optimum Learning](https://out-image/Q-Learning%20Agent%20Final%20Result%20Learning.png)
Fig2. Optimum Learning
![Heatmap Q Values](https://out-image/Q-Learning%20Heatmap%20Q%20Values.png)
Fig3. Heatmap Q Values
