# Performance Evaluation of Dijkstra and A* Algorithms
![Python](https://img.shields.io/badge/Language-Python-3776AB?logo=python&logoColor=white)
![LaTeX](https://img.shields.io/badge/Report-LaTeX-008080?logo=latex&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-11557c)

![Domain](https://img.shields.io/badge/Domain-IoT_%26_Autonomous_Systems-4CAF50)
![Algorithms](https://img.shields.io/badge/Algorithms-Dijkstra_%7C_A*-F28D1A)
![Heuristics](https://img.shields.io/badge/Heuristics-Manhattan_%7C_Euclidean-9B59B6)

![Repo Size](https://img.shields.io/github/repo-size/G-Danush/Performance-Evaluation-of-Dijkstra-and-A-Algorithms)
![Last Commit](https://img.shields.io/github/last-commit/G-Danush/Performance-Evaluation-of-Dijkstra-and-A-Algorithms)
![GitHub stars](https://img.shields.io/github/stars/G-Danush/iSWaMS-IoT-Smart-Waste-Management?style=social)

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
