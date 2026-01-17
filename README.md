# Autonomous Vehicle Path Planning (A*)

This repository contains a Python implementation of the **A* Search Algorithm** designed for autonomous vehicle navigation within a simulated environment.

## Overview

The project demonstrates a "Sense-Plan-Act" pipeline for automotive engineering, focusing on the **Navigation** layer. It uses a grid-based occupancy map to identify obstacles and calculate the mathematically optimal path from a start coordinate to a destination.

## Key Features

- **Perception Modeling:** Uses a 2D NumPy array to represent an occupancy grid (0 for free space, 1 for obstacles).
- **A* Implementation:** Utilizes a priority queue (`heapq`) for efficient search and an admissible Euclidean heuristic.
- **Visualization:** Integrated `matplotlib` functions to render the grid-map, obstacles, and calculated trajectory.
- **Verification:** An automated testing suite to validate path optimality and obstacle avoidance.

## Project Structure

* **Algorithm Logic:** Core A* implementation including  cost calculations.
* **Scenario Setup:** Grid preparation representing an environment with static obstacles.
* **Results & Analysis:** Performance evaluation based on optimality, efficiency, and completeness.

## How It Works

1. Have a conversation with the assistant on the interview you want to prepare for
2. Speak naturally with the AI interviewer
3. Start an AI simulated interview
4. Receive instant, detailed feedback on your performance

## Getting Started

### Prerequisites

- Python 3.x
- NumPy
- Matplotlib

### Installation

- Open the `.ipynb` file in Google Colab.
- Run the cells sequentially to define the algorithm and helper functions.
- Execute the final cells to generate the pathfinding visualization.

## Ethical & Environmental Considerations

The project includes a brief analysis of Responsible AI practices, focusing on:

- **Sustainability:** Reducing computational overhead via hierarchical planning.
- **Fairness:** Addressing bias in spatial navigation and accessibility.
