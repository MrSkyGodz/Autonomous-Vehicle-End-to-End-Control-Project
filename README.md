# Ros Perception Controller Project
In this project, we have an application for simulating autonomous vehicle behavior, which includes both perception and controller modules.

### Components of the Application:

1. **Simulation Environment:**
   - There is a simulation environment to test our autonomous vehicles. This environment simulates road scenarios and various environmental conditions.

2. **Perception Module:**
   - During the vehicle simulation, captured images are processed by the perception module. This module analyzes the road, segmentate lanes, and determines waypoints necessary to determine the vehicle's position.

3. **Controller Module:**
   - The controller module directs the vehicle's movement using information from the perception module. It adjusts the vehicle's speed and orientation based on the identified waypoints.

 
## Initilize the Project
For cloning repository use this command because this repository include submodules.
```
git clone --recursive *repository*
```
If you aldready cloned repository use this command to update submodules.
```
git submodule update --init --recursive
```
## Objective
Your objective is inside the [perception_and_controller](https://github.com/MrSkyGodz/perception_and_controller/) module.

## Run Commands
For build packages. Use this command inside of this directory.
```
colcon build
```
For launch smulation module.
```
ros2 launch gazebo_project sonoma.launch.py
```
For run perception module.
```
ros2 run perception_and_controller perception
```
For run controlle module
```
ros2 run perception_and_controller controller
```