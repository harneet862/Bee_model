# Bee_model
## Overview:
The Bee Simulation Project is designed to analyze bee interactions and behaviors using a simulation model built with the Python Mesa module. The project aims to track bee trajectories, calculate interaction probabilities, and enhance the understanding of bee dynamics in various environments.

## Table of Contents
- Features
- Technologies Used
- Installation
- Usage
- References

## Features
- Simulates interactions among up to 400 bees.
- Tracks the trajectories of 40 bees using video analysis.
- Calculates interaction probabilities based on trajectory data.
- Iteratively enhances the simulation model using 10-hour video recordings.
- Implements a user-friendly frontend with sliders for adjusting model parameters.
  
## Technologies Used
- Programming Language: Python
- Simulation Framework: Mesa
- Video Analysis: OpenCV
- Data Manipulation: Pandas, NumPy
- Visualization: Matplotlib
- User Interface Design: Figma
  
## Installation
1. Clone the repository:
`git clone https://github.com/harneet862/Bee_model.git`
2. Install the required dependencies:
`pip install mesa opencv-python pandas numpy matplotlib`
3. Ensure you have the necessary data files and videos for analysis.

## Usage
- Run the simulation model:
`python run.py`
and use the link to open the frontend
- Use sliders to change the simulation parameters such as the number of bees and interaction thresholds.
- Analyze the output visualization to observe bee interactions and behaviors.

## References
1. https://github.com/rcterrile/Trophallaxis_Mesa_Discrete
