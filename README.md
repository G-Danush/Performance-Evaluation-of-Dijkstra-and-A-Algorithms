# Performance Evaluation of Dijkstra and A* Algorithms

This repository contains the source code and formal LaTeX report for my assignment in the **Technologies for IoT & Autonomous Systems** course at IIIT Sri City. 

## Project Overview
This project evaluates and compares the performance of Dijkstra's Algorithm and the A* Search Algorithm. The algorithms were tested on simulated real-world map grids of varying sizes (15, 75, and 250 nodes) to benchmark their execution times and memory (nodes explored).

For the A* algorithm, two distinct heuristics were implemented and compared:
- **Euclidean Distance**
- **Manhattan Distance**

## Repository Structure
- `pathfinding.py`: The complete Python implementation of the algorithms, graph generation, and Matplotlib visualizations.
- `report.tex`: The LaTeX source code for the formal academic report.
- `report.pdf`: The compiled final report including complexity analysis, tabular comparisons, and expected observations.
- `download.png`: The output performance graphs.

## How to Run
The code requires Python 3 and the `matplotlib` library.
1. Clone this repository.
2. Run the script: `python pathfinding.py`
3. Follow the on-screen prompts (press `Enter`) to step through the 15-node, 75-node, and 250-node network evaluations. 

## Author
**Guntupalli Danush** (OMIO25S00020)  
M.Tech, IoT and Autonomous Systems
