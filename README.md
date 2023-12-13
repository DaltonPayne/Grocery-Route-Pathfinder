# Grocery-Route-Pathfinder

## Overview
This repository contains a Python notebook designed to demonstrate the application of pathfinding algorithms in a grocery store context. The script simulates the process of finding the shortest route to collect a list of items in a grocery store. It explores all possible permutations of routes and visualizes the most optimal path.

## Features
- **Grocery Store Layout Simulation:** Generates a simulated layout of a grocery store, complete with aisles, sections, and a staging area.
- **Item Placement:** Randomly places items (picks) in the store layout.
- **Pathfinding Algorithms:** Utilizes A* search algorithm for efficient pathfinding.
- **Route Optimization:** Implements an exhaustive method to find the shortest path for collecting all items (Traveling Salesman Problem approach).
- **Visualization:** Provides a visual representation of the grocery store layout and the optimized path for item collection.

## Usage
To use this notebook:
1. Clone the repository to your local machine.
2. Ensure required libraries are installed (`numpy`, `heapq`, `itertools`, `matplotlib`, `scipy`).
3. Run the notebook cells.

## Functions
- `create_grocery_layout_with_staging_area()`: Initializes the grocery store layout.
- `place_random_picks(layout, num_picks)`: Places a specified number of items randomly in the store layout.
- `a_star_search(start, goal, grid)`: Implements A* search algorithm for pathfinding.
- `find_shortest_tsp_path(all_paths, staging_area, picks)`: Solves for the shortest path using a Traveling Salesman Problem approach.
- `visualize_layout(layout, path)`: Visualizes the grocery store layout and the chosen path.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
