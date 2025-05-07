Here's a clean, readable README.md file:

# Robot Navigation Interface

This repository contains a ROS-based robot navigation system with a Jupyter Notebook interface for controlling and monitoring the robot.

## Requirements

- ROS Noetic
- Python 3
- Jupyter Notebook
- Required Python packages: jupyros, ipywidgets, matplotlib, numpy

## How to Run

### 1. Launch the Simulation

Open a terminal and run:
```bash
source /opt/ros/noetic/setup.bash
source ~/catkin_ws/devel/setup.bash
roslaunch assignment_2_2024 sim_w1.launch
```

### 2. Launch Jupyter Notebook

Open a new terminal and run:
```bash
source /opt/ros/noetic/setup.bash
source ~/catkin_ws/devel/setup.bash
jupyter notebook
```

### 3. Using the Interface

The Jupyter notebook interface provides:
- Real-time robot position visualization
- Target setting functionality
- Obstacle distance monitoring
- Navigation statistics

## Features

- Interactive robot control through a graphical interface
- Real-time position tracking
- Obstacle detection and distance monitoring
- Target completion statistics
- Visual feedback of robot's path

## Troubleshooting

If you encounter issues:
- Ensure both terminals have properly sourced ROS setup files
- Verify the simulation is running before opening the notebook
- Check that all ROS topics are publishing correctly

## Note

Keep both terminals running while using the system. The first terminal runs the simulation, and the second runs the Jupyter notebook interface. 
