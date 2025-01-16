Line Follower Drone (MATLAB)
Introduction
This repository contains the MATLAB code for a line follower drone, developed as part of a drone competition organized by MathWorks. The project involves various components including controllers, airframe models, and utility functions to enable the drone to follow a predefined path.

Repository Structure
controller/: Contains the control algorithms used for the drone.

libraries/: Includes any external libraries or dependencies required for the project.

linearAirframe/: Models and simulations related to the linear airframe of the drone.

mainModels/: Main models used in the project, including both linear and nonlinear models.

nonlinearAirframe/: Models and simulations related to the nonlinear airframe of the drone.

resources/project/: Additional resources and project files.

support/: Support files and scripts.

tasks/: Task-specific scripts and functions.

tests/: Testing scripts to validate the functionality of the code.

utilities/: Utility functions and scripts used throughout the project.

work/: Workspace files and temporary scripts.

Getting Started
Clone the repository:

sh
git clone https://github.com/yourusername/line-follower-drone.git
Navigate to the project directory:

sh
cd line-follower-drone
Open MATLAB and add the project directory to the MATLAB path:

matlab
addpath(genpath('path_to_project_directory'))
Usage
Running Simulations: Use the scripts in the mainModels folder to run simulations of the drone following a line.

Testing: Execute the scripts in the tests folder to validate the performance and accuracy of the control algorithms.

Modifying Control Algorithms:
