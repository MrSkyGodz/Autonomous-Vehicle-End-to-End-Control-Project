# Ros Perception Controller Project
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
Your objective is inside the [perception_and_controller.](https://github.com/MrSkyGodz/perception_and_controller/)

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