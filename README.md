# Bee_model
## Overview:
The Bee Simulation Project is designed to analyze bee interactions and behaviors using a simulation model built with the Python Mesa module. The project aims to enhance the understanding of bee dynamics by mimicing the experimental setup and providing the option to change the parameters.

## Table of Contents
- Features
- Technologies Used
- Installation
- Usage
- References

## Features
- Simulates interactions among up to 400 bees.
- Implements a user-friendly frontend with sliders for adjusting model parameters.
- Identifies the nearest bee within the simulation environment based on proximity.
- Facilitates the exchange of food between bees according to predefined parameters.
- Simulates the transfer of viruses between bees, reflecting realistic interactions.
- Tracks and provides analytics on:
  - The total amount of food shared among bees throughout the simulation.
  - The total amount of virus transmitted during interactions.
- Updates analytics continuously as the simulation progresses, allowing for insights into bee interactions.
  
## Technologies Used
- Programming Language: Python
- Simulation Framework: Mesa
- Data Manipulation: Pandas, NumPy
    
## Installation
1. Clone the repository:
`git clone https://github.com/harneet862/Bee_model.git`
2. Install the required dependencies:
`pip install mesa pandas numpy `
3. Ensure you have the necessary data files and videos for analysis.

## Usage
- Run the simulation model:
`python run.py`
and use the link to open the frontend
- Use sliders to change the simulation parameters such as the number of bees and interaction thresholds.
- Analyze the output visualization to observe bee interactions and behaviors.

## References
1. https://github.com/rcterrile/Trophallaxis_Mesa_Discrete
