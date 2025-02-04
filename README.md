# 1、ACO Path Planning in MATLAB
# This repository contains MATLAB code for an Ant Colony Optimization (ACO) based robot path planning algorithm. The code uses a grid map, where obstacles are marked by 1 and free spaces by 0, and finds a path from a start node to a target node.

# Files
# main.m: Main function that implements the ACO algorithm and plots the results.
# G2D.m: Helper function that converts the grid map into an adjacency (distance) matrix.

# Usage
# Open MATLAB and navigate to the repository folder.
# Run the main function: main.

# The algorithm will run, and figures showing the convergence curve and robot trajectory will be displayed.

# 2、ACO Path Planning in ROS
# This repository contains a ROS C++ implementation of an Ant Colony Optimization (ACO) based global planner. The planner uses a costmap, an occupancy grid (OGM), and a pheromone matrix to generate a global path for a robot.
# Files
# aco.cpp / aco.h: Implementation of the ACO algorithm.
# AcoPlannerROS.cpp: The ROS interface for the global planner.
# Other necessary ROS package files (CMakeLists.txt, package.xml, etc.).

# Usage
# Clone the repository into your ROS workspace.
# Build the package using: catkin_make
# Source your workspace: source devel/setup.bash
# Launch your ROS application that uses the global planner.
