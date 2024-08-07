# AI-Project2

## Description
Developed a multi-agent system consisting of 8 autonomous bots designed to navigate a ship layout, detect and avoid obstacles, locate crew members, and rescue them while avoiding alien threats. Implemented advanced pathfinding algorithms and probabilistic models for sensor data interpretation and decision-making.

## Technologies Used
Python, NumPy, Matplotlib, Seaborn, A* Algorithm, Manhattan Distance, Priority Queue, Random Module, Copy Module

## Key Features and Contributions
- Ship Layout Generation:
  Created algorithms to generate random ship layouts with defined open and blocked cells.
  Implemented functions to identify open and blocked neighbors, and detect dead-end cells.
- Pathfinding with A Algorithm:*
  Developed the A* algorithm for optimal pathfinding from the bot's start position to the crew’s location.
  Calculated Manhattan distances for heuristic evaluations.
- Sensor and Detection Systems:
  Designed sensor cells for alien detection within a (2k+1) x (2k+1) grid around each bot.
  Implemented crew and alien beep detection based on sensor inputs and probabilistic models.
- Probabilistic Models:
  Created probabilistic models to update crew and alien location probabilities based on sensor data and movement.
  Normalized probability distributions after each bot and alien movement.
- Alien Movement and Game Status:
  Developed functions for alien movement and checking game status after each bot move.
  Simulated alien movements and updated game status (SUCCESS/FAILURE) based on bot and alien positions.
- Heatmap Visualization:
  Used Seaborn to create heatmaps for visualizing crew and alien probability distributions.
- Simulation and Main Method:
  Initiated bot, crew, and alien positions on the ship.
  Ran simulations for each bot, updating probabilities and checking game status iteratively.
  Achieved successful crew rescue with the simulation showing bot status as SUCCESS.
## Outcome
Successfully simulated the navigation and rescue operations of 8 autonomous bots, demonstrating efficient pathfinding, probabilistic reasoning, and real-time decision-making in a dynamic environment.
